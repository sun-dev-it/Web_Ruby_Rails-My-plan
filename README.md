```markdown
# SAP Code Snippet

Here's an example of SAP code you can use in your projects:

```abap
REPORT ZTEST_REPORT.

PARAMETERS: p_name TYPE char30 OBLIGATORY.

START-OF-SELECTION.

  WRITE: / 'Hello, ', p_name, '!'.
