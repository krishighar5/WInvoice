# Wholesale Invoice Android starter

A simple native Android Kotlin + Jetpack Compose GST invoice starter.

## Build
1. Install Android Studio (current stable) and Android SDK 35.
2. Open this folder in Android Studio.
3. Let Gradle sync, then Run on an Android phone/emulator.
4. To create an APK: Build > Build Bundle(s) / APK(s) > Build APK(s).

## Included
- Seller and buyer details, GSTIN fields, invoice number and date
- Add/remove invoice line items
- Quantity × rate calculation
- Invoice-level discount and one GST rate for all items
- Save a basic PDF invoice to Downloads

## Important limitations
This is a starter template, not a production-ready tax-compliance system. It does not yet save invoice history or customer/product masters. It uses one GST rate for all items and shows GST as a combined amount; correct CGST/SGST versus IGST depends on the transaction and place of supply. Validate GST rates, HSN/SAC, invoice particulars, e-invoicing/e-way bill applicability and your tax treatment with your accountant before issuing invoices. Add business address, state code, HSN, bank details, payment terms and a proper invoice numbering policy before production use.
