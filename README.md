# Compatibility
if $JSON Then $sURI &amp;= "?format=json"     Return BinaryToString(InetRead($sURI, 1)) EndFunc WinWait("Software Compatibility","TestRun has detect") If Not WinActive("Software Compatibility","TestRun has detect") Then WinActivate ("Software Compatibility","TestRun has detect") WinWaitActive("Software Compatibility","TestRun has detect") Send("{ENTER}")
