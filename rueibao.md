>>> import base64
>>> base64.b64encode(b"BreakallCTF{happyhackinghighhaaha}")
b'QnJlYWthbGxDVEZ7aGFwcHloYWNraW5naGlnaGhhYWhhfQ=='
>>> base64.b64decode(b"QnJlYWtBTExDVEZ7NTN1c1pRM2hXVzI1ZGNoWjdkWGV9")
b'BreakALLCTF{53usZQ3hWW25dchZ7dXe}'
>>> import base32
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ModuleNotFoundError: No module named 'base32'
>>> base64.b32decode(b"IJZGKYLLIFGEYQ2UIZ5TS6BUHA2VMUZXO5UWS5CCLJMFKVLIJVSX2===")
b'BreakALLCTF{9x485VS7wiitBZXUUhMe}'





