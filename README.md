# fastersheets
Getting Things Done Quickly with Excel (or Google Sheets)

## Add Multiple Rows Between Rows (Google Sheets)

`=TRANSPOSE(Split(join(", , ,",ArrayFormula((A2:A103))),","))`
