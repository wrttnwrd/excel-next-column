Automatically detect next column in Excel

Use this, or download the text file:

=OFFSET(B$1,0,ROW(L1)-1)

or, for a range:

=OFFSET(B$1,0,ROW(O2)-2):OFFSET(B$118,0,ROW(O2)-2))
