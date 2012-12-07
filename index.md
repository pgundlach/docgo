---
title: docgo
layout: default
---

docgo

## ABOUT

docgo is a lightweight literate-programming-style documentation generator for
Go source code.  It is modeled on Jeremy Ashkenas's docco.  See
dhconnelly.github.com/docgo for the result of running docgo on its source code.

## INSTALLATION

go get github.com/dhconnelly/docgo

## USAGE

Just run

docgo source.go

where source.go is a Go source file in the current directory.  This creates
the file source.html in the current directory, a self-contained HTML page
containing your annotated source code.

## AUTHOR

docgo was written by Daniel Connelly.  You can find my stuff at dhconnelly.com.

## LICENSE

docgo is released under a BSD-style license available in LICENSE.md.