---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

{% include base_path %}

<div class="cv-content">
  <div class="cv-toolbar">
    <a href="{{ base_path }}/files/Subin_CV_1016.pdf" class="cv-button" download="Subin_CV_1016.pdf">
      📄 Download CV (PDF)
    </a>
    <a href="{{ base_path }}/files/Subin_CV_1016.pdf" class="cv-button cv-button-ghost" target="_blank" rel="noopener">
      Open in new tab
    </a>
    <span class="cv-updated">Last updated: October 2026</span>
  </div>

  <div class="cv-preview">
    <object data="{{ base_path }}/files/Subin_CV_1016.pdf#view=FitH" type="application/pdf" aria-label="Preview of Subin Na's CV">
      <div class="cv-preview-fallback">
        <p>The inline preview could not load in this browser.</p>
        <a href="{{ base_path }}/files/Subin_CV_1016.pdf" class="cv-button" target="_blank" rel="noopener">Open the CV (PDF)</a>
      </div>
    </object>
  </div>
</div>

<style>
  .cv-content {
    min-height: 60vh;
  }
  .cv-toolbar {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 0.8em 1em;
    margin-bottom: 1.6em;
  }
  .cv-button {
    display: inline-block;
    background-color: #011F5B;
    color: #ffffff !important;
    padding: 12px 28px;
    border-radius: 4px;
    text-decoration: none !important;
    font-weight: 500;
    font-size: 1em;
    transition: background-color 0.2s ease, color 0.2s ease;
    border: 2px solid #011F5B;
  }
  .cv-button:hover {
    background-color: #ffffff;
    color: #011F5B !important;
    text-decoration: none !important;
  }
  .cv-button-ghost {
    background-color: #ffffff;
    color: #011F5B !important;
  }
  .cv-button-ghost:hover {
    background-color: #011F5B;
    color: #ffffff !important;
  }
  .cv-updated {
    color: #666;
    font-size: 0.9em;
  }
  .cv-preview {
    position: relative;
    width: 100%;
    height: 85vh;
    min-height: 600px;
    border: 1px solid #d7deea;
    border-radius: 6px;
    overflow: hidden;
    background: #f7f5f0;
    box-shadow: 0 1px 4px rgba(0,0,0,0.06);
  }
  .cv-preview object {
    display: block;
    width: 100%;
    height: 100%;
  }
  .cv-preview-fallback {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 1em;
    height: 100%;
    padding: 2em;
    text-align: center;
    color: #444;
  }
  @media (max-width: 768px) {
    .cv-preview {
      height: 70vh;
      min-height: 480px;
    }
  }
</style>
