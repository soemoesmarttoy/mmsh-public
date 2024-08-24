---
layout: default
title: ငွေကြေးစီးဆင်းမှု အမျိုးအစားများ
date: 2024-08-23
tag: knowledge
---

### မတည်ရင်းနှီးငွေနှင့် ထုတ်ယူခြင်းဆိုင်ရာ
- first_equity_added
  - ပထမဦးဆုံး ငွေအကောင့်တစ်ခု ထည့်သွင်းခြင်း
  - credit => Equity 
  - debit => Cash
- added_equity
  - ငွေအကောင့်အသစ် သို့မဟုတ် ရှိပြီးအကောင့်သို့ အရင်းအနှီး ထပ်မံထည့်သွင်း‌ခြင်း
  - credit => Equity 
  - debit => Cash
- reduced_equity
  - ငွေအကောင့်မှ အရင်းအနှီးထုတ်ယူခြင်း
  - credit => Cash
  - debit => Equity
- took_out_retained_earnings
  - စုဆောင်းအမြတ်မှ ငွေထုတ်ယူခြင်း
  - credit => Cash
  - debit => Retained Earnings
- transferred_cash
  - ‌ငွေအကောင့် တစ်ခုမှ တစ်ခုသို့ ငွေလွှဲပြောင်းခြင်း
  - credit => Cash
  - debit => Cash

### အဝယ်လုပ်ငန်းစဥ်ဆိုင်ရာများ
- buy_settled_by_cash
  - လက်ငင်းငွေချေ၍ ဝယ်ယူခြင်း
  - debit => Inventory
  - credit => Cash
- buy_fixed_asset_by_cash
  - ‌အဆောက်အဦးနှင့် စက်ပစ္စည်းအစရှိသည့် ရေရှည်ရပိုင်ခွင့်များကို လက်ငင်းငွေချေ၍ ဝယ်ယူခြင်း
  - deibt - Fixed Assets
  - credit => Cash
- buy_add_payables
  - ကုန်ပစ္စည်းများကို အကြွေးဖြင့်ဝယ်ယူခြင်း (ပေးရန်ရှိ)
  - debit => Inventory
  - credit => Payables

### အရောင်းလုပ်ငန်းစဥ်ဆိုင်ရာများ
- sell_settled_by_cash
  - ကုန်ပစ္စည်းများကို လက်ငင်းငွေလက်ခံကာ ‌ရောင်းချခြင်း
  - credit => Inventory
  - debit => COGS
  - credit => Sale
  - debit => Cash
- sell_add_receivables
	- အကြွေးနှင့်ရောင်းချခြင်း
	- credit => Inventory
  - debit => COGS
  - credit => Sale
  - debit => Receivables
- sell_fixed_asset_settled_by_cash
	- အဆောက်အဦးနှင့် စက်ပစ္စည်းအစရှိသည့် ရေရှည်ရပိုင်ခွင့်များကို‌ လက်ငင်းငွေလက်ခံကာ ရောင်းချခြင်း
	- credit => Fixed Asset
  - debit => Cash
  - credit => Fixed Asset
  - debit => Expenses Fixed Asset Sold (ရောင်းစျေးပိုများသောအခါ) 
  - credit => Incomes Fixed Assets Sold
  - debit => Fixed Asset(ရောင်းစျေးပိုနည်းသောအခါ)
- sell_fixed_asset_add_receivables
	- အဆောက်အဦးနှင့် စက်ပစ္စည်းအစရှိသည့် ရေရှည်ရပိုင်ခွင့်များကို‌ အကြွေးဖြင့် ရောင်းချခြင်း
	- credit => Fixed Asset
  - debit => Receivables
  - credit => Fixed Asset
  - debit => Expenses Fixed Asset Sold (ရောင်းစျေးပိုများသောအခါ) 
  - credit => Incomes Fixed Assets Sold
  - debit => Fixed Asset(ရောင်းစျေးပိုနည်းသောအခါ)

### ပေးရန်ရှိနှင့် ဆိုင်ရာများ (Payables related)
- added_payables
	- ငွေကြိုလက်ခံထားခြင်း
	- credit => Cash
  - debit => Payables
- reversed_payables
	- လက်ခံထားသောငွေအားလုံးအား ပြန်လည်ထုတ်ပေးခြင်း
	- debit => Cash
  - credit => Payables
- reduced_payables
	- လက်ခံထားသောငွေ ပေးရန်ရှိ တစ်စောင်မှ အချို့သောငွေအား ပြန်လည်ထုတ်ပေးခြင်း
	- debit => Cash
  - credit => Payables
- paid_payables_by_cash
	- အကြွေးနှင့်ဝယ်ယူထားသော ပေးရန်ရှိတစ်စောင်မှ ကျန်ရှိသော ငွေအားလုံးကို လက်ငင်းငွေသားဖြင့် ပြန်လည်ပေးဆပ်ခြင်း
	-  credit => Cash
  - debit => Payables - 
- partially_paid_payables_by_cash
	- အကြွေးနှင့်ဝယ်ယူထားသော ပေးရန်ရှိတစ်စောင်မှ ကျန်ရှိသော ငွေအချို့ကို လက်ငင်းငွေသားဖြင့် ပြန်လည်ပေးဆပ်ခြင်း
	-  credit => Cash
  - debit => Payables
- paid_payables_by_cash_pre_paid
	- အကြွေးနှင့်ဝယ်ယူထားသော ပေးရန်ရှိတစ်စောင်မှ ကျန်ရှိသော ငွေအားလုံးကို ကြိုတင်ထုတ်ပေးထားသော ရရန်ရှိတစ်စောင်ဖြင့် ပြန်လည်ပေးဆပ်ခြင်း
	- credit => Receivables
  - debit => Payables
- partially_paid_payables_by_cash_pre_paid
	- အကြွေးနှင့်ဝယ်ယူထားသော ပေးရန်ရှိတစ်စောင်မှ ကျန်ရှိသော  ငွေအချို့ကို ကြိုတင်ထုတ်ပေးထားသော ရရန်ရှိတစ်စောင်ဖြင့် ပြန်လည်ပေးဆပ်ခြင်း
	- credit => Receivables
  - debit => Payables
- paid_payables_by_receivables
  အကြွေးနှင့်ဝယ်ယူထားသော ပေးရန်ရှိတစ်စောင်မှ ကျန်ရှိသော ငွေအားလုံးကို အကြွေးဖြင့်ရောင်းချထားသော ရရန်ရှိတစ်စောင်ဖြင့် ပြန်လည်ပေးဆပ်ခြင်း
	- credit => Receivables
  - debit => Payables
- partially_paid_payables_by_receivables
	- အကြွေးနှင့်ဝယ်ယူထားသော ပေးရန်ရှိတစ်စောင်မှ ကျန်ရှိသော ငွေအချို့ကို အကြွေးဖြင့်ရောင်းချထားသော ရရန်ရှိတစ်စောင်ဖြင့် ပြန်လည်ပေးဆပ်ခြင်း
	- credit => Receivables
  - debit => Payables

### ရရန်ရှိနှင့်သက်ဆိုင်ရာများ (ပေးရန်ရှိ ပြောင်းပြန်ဟု ယူဆရန်)
  - added_receivables
  - reversed_receivables
  - received_receivables_by_cash
  - partially_received_receivables_by_cash
  - received_receivables_by_cash_pre_received
  - partially_receivables_by_cash_pre_received
  - received_receivables_by_payables
  - partially_received_receivables_by_payables

### ကုန်ထုတ်လုပ်ငန်းဆိုင်ရာများ
  - output_amount_added_in_progress
	  - ကုန်‌ထုတ်လုပ်ငန်းတစ်ခု မပြီးဆုံးသေးခင် လက်ရှိထွက်ရှိနေသော ‌ကုန်ချော အရေအတွက်များကို ထည့်သွင်းသောအခါ ထုတ်လုပ်ဆဲ အကောင့်များတွင် ခဏသွင်းထားပေးခြင်း
	  - credit => Inventory
	  - debit => InProgress
  - product_exchanged
	  - ကုန်ပစ္စည်းတစ်ခုမှတစ်ခုသို့ ပြောင်းလဲခြင်း
	  - credit => Inventory
    - debit => Inventory
    - added_cogs
    - လက်ကျန်မရှိသော ကုန်ကို ‌ရောင်းချထားပြီး ၄င်းကုန်ပစ္စည်းသည် ကုန်ချောအဖြစ် ကုန်ထုတ်လုပ်ငန်းမှ ထွက်ရှိလာသောအခါ ရောင်းချထားသော ကုန်ပစ္စည်း၏ ကုန်ရင်းတန်ဖိုးကို ထည့်‌သွင်းပေးခြင်း
    - credit => Inventory 
    - debit => COGS 
    - debit => Inventory
    - credit => Inventory
  - input_amount_deducted
	  - ကုန်ထုတ်လုပ်ငန်း စတင်ထုတ်လုပ်သောအခါ အသုံးပြုမည့် ကုန်ကြမ်းတန်ဖိုးအား နှုတ်ယူခြင်း
	  - credit => Inventory
  - output_amount_added
	  - ကုန်ထုတ်လုပ်ငန်း ပြီးစီးသောအခါ ထွက်ရှိလာသော ကုန်ချောများ၏ ကုန်ရင်းတန်းဖိုးကို ထည့်သွင်းခြင်း
	  - debit => Inventory
	  - debit => Inventory
    - credit => InProgress (sometimes)

### အခြား
  - incomes_from_fixed_asset_sold
  - expenses_from_fixed_asset_sold
  - rent_by_receivables
  - rent_by_cash
  - consignment_created
  - consignment_amount_added
  - consignment_settled_by_cash
  - consignment_add_receivables
  - consignment_returned
  - added_expenses
  - added_other_incomes_by_cash
  - spare_part_added