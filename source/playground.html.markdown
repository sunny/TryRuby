---
title: "TryRuby playground"
description: Play around with Ruby programs
---

<div class="row">
  <div class="col-md-6">
    <h2 id="tryruby-title">Playground</h2>
    <div id="tryruby-content">
      <div class="playground-iframe-wrapper">
        <iframe
          src="https://www.ruby-doc.org/core/Kernel.html"
        >www.ruby-doc.org</iframe>
      </div>

      <p>
        In the Playground you can try any Ruby code you like.<br />
        The
        <a href="https://www.ruby-doc.org/core/Kernel.html" target="_blank">Ruby documentation</a>
        is included.
      </p>
    </div>
  </div>

  <div class="col-md-6">

    <h2 class="code-title">Editor</h2>
    <div id="editor" class="well" style="padding:0"></div>

    <div class="row">
      <div class="offset-md-8 col-md-4">
        <button type="button" id="btn_run" class="btn btn-primary btn-block">
          Run
        </button>
      </div>
    </div>

    <h2 class="code-title">Output</h2>
    <div id="output" class="tryruby-output"></div>
  </div>
</div>
