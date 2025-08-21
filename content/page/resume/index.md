+++
draft = false
title = 'My Resume'
toc = false
readingTime = false
comments = false
+++

<div class="resume-actions">
    <a href="/devhub/resume.pdf" download="YourName_Resume.pdf" class="btn btn-primary">
        <svg width="16" height="16" fill="currentColor" viewBox="0 0 16 16" style="margin-right: 8px;">
            <path d="M.5 9.9a.5.5 0 0 1 .5.5v2.5a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-2.5a.5.5 0 0 1 1 0v2.5a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2v-2.5a.5.5 0 0 1 .5-.5z"/>
            <path d="M7.646 11.854a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0-.708-.708L8.5 10.293V1.5a.5.5 0 0 0-1 0v8.793L5.354 8.146a.5.5 0 1 0-.708.708l3 3z"/>
        </svg>
        Download PDF
    </a>
    <a href="/devhub/resume.pdf" target="_blank" class="btn btn-outline">
        <svg width="16" height="16" fill="currentColor" viewBox="0 0 16 16" style="margin-right: 8px;">
            <path fill-rule="evenodd" d="M8.636 3.5a.5.5 0 0 0-.5-.5H1.5A1.5 1.5 0 0 0 0 4.5v10A1.5 1.5 0 0 0 1.5 16h10a1.5 1.5 0 0 0 1.5-1.5V7.864a.5.5 0 0 0-1 0V14.5a.5.5 0 0 1-.5.5h-10a.5.5 0 0 1-.5-.5v-10a.5.5 0 0 1 .5-.5h6.636a.5.5 0 0 0 .5-.5z"/>
            <path fill-rule="evenodd" d="M16 .5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0 0 1h3.793L6.146 9.146a.5.5 0 1 0 .708.708L15 1.707V5.5a.5.5 0 0 0 1 0v-5z"/>
        </svg>
        Open in New Tab
    </a>
</div>

<div class="resume-viewer">
    <div class="resume-embed">
        <embed src="/devhub/resume.pdf" type="application/pdf" width="100%" height="100%">
    </div>
    <div class="resume-fallback">
        <div class="alert alert-info">
            <svg width="16" height="16" fill="currentColor" viewBox="0 0 16 16" style="margin-right: 8px;">
                <path d="M8 16A8 8 0 1 0 8 0a8 8 0 0 0 0 16zm.93-9.412-1 4.705c-.07.34.029.533.304.533.194 0 .487-.07.686-.246l-.088.416c-.287.346-.92.598-1.465.598-.703 0-1.002-.422-.808-1.319l.738-3.468c.064-.293.006-.399-.287-.47l-.451-.081.082-.381 2.29-.287zM8 5.5a1 1 0 1 1 0-2 1 1 0 0 1 0 2z"/>
            </svg>
            <strong>PDF Viewer:</strong> If the PDF doesn't display properly, you can <a href="/devhub/resume.pdf" target="_blank">view it in a new tab</a> or download it using the button above.
        </div>
    </div>
</div>

<style>
.resume-actions {
    display: flex;
    gap: 12px;
    justify-content: center;
    align-items: center;
    margin: 24px 0 32px 0;
    flex-wrap: wrap;
}

.btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 8px 16px;
    font-size: 14px;
    font-weight: 500;
    line-height: 1.43;
    border-radius: 6px;
    border: 1px solid;
    text-decoration: none;
    cursor: pointer;
    transition: all 0.15s ease;
    white-space: nowrap;
    font-family: var(--base-font-family);
}

.btn-primary {
    background: var(--gh-accent-emphasis, #0969da);
    border-color: var(--gh-accent-emphasis, #0969da);
    color: white;
}

.btn-primary:hover {
    background: var(--gh-accent-fg, #0550ae);
    border-color: var(--gh-accent-fg, #0550ae);
    color: white;
    text-decoration: none;
    transform: translateY(-1px);
    box-shadow: var(--shadow-l1);
}

.btn-outline {
    background: var(--card-background, #ffffff);
    border-color: var(--gh-border-default, #d1d9e0);
    color: var(--card-text-color-main, #1f2328);
}

.btn-outline:hover {
    background: var(--gh-canvas-subtle, #f6f8fa);
    border-color: var(--gh-neutral-emphasis, #656d76);
    color: var(--card-text-color-main, #1f2328);
    text-decoration: none;
    transform: translateY(-1px);
    box-shadow: var(--shadow-l1);
}

.resume-viewer {
    width: 100%;
    height: 800px;
    border: 1px solid var(--gh-border-default, #d1d9e0);
    border-radius: 12px;
    overflow: hidden;
    background: var(--card-background, #ffffff);
    box-shadow: var(--shadow-l2);
    position: relative;
}

.resume-embed {
    width: 100%;
    height: 100%;
}

.resume-embed embed {
    border-radius: 12px;
}

.resume-fallback {
    position: absolute;
    bottom: 16px;
    left: 16px;
    right: 16px;
    pointer-events: none;
}

.resume-fallback .alert {
    pointer-events: all;
}

.alert {
    display: flex;
    align-items: flex-start;
    padding: 12px 16px;
    border-radius: 6px;
    border: 1px solid;
    margin: 0;
    font-size: 14px;
    line-height: 1.43;
}

.alert-info {
    background: rgba(9, 105, 218, 0.1);
    border-color: var(--gh-accent-emphasis, #0969da);
    color: var(--card-text-color-main, #1f2328);
}

.alert svg {
    flex-shrink: 0;
    margin-top: 2px;
}

.alert strong {
    font-weight: 600;
}

.alert a {
    color: var(--gh-accent-fg, #0550ae);
    text-decoration: underline;
}

.alert a:hover {
    text-decoration: none;
}

/* Dark mode adjustments */
:root[data-scheme="dark"] .btn-outline {
    background: var(--card-background, #161b22);
    border-color: var(--gh-border-default, #30363d);
    color: var(--card-text-color-main, #e6edf3);
}

:root[data-scheme="dark"] .btn-outline:hover {
    background: var(--gh-canvas-default, #0d1117);
    border-color: var(--gh-neutral-emphasis, #7d8590);
    color: var(--card-text-color-main, #e6edf3);
}

:root[data-scheme="dark"] .resume-viewer {
    border-color: var(--gh-border-default, #30363d);
    background: var(--card-background, #161b22);
}

:root[data-scheme="dark"] .alert-info {
    background: rgba(47, 129, 247, 0.15);
    border-color: var(--gh-accent-emphasis, #2f81f7);
    color: var(--card-text-color-main, #e6edf3);
}

/* Responsive design */
@media (max-width: 768px) {
    .resume-actions {
        flex-direction: column;
        gap: 8px;
    }
    
    .btn {
        width: 100%;
        max-width: 280px;
    }
    
    .resume-viewer {
        height: 600px;
        border-radius: 8px;
    }
    
    .resume-fallback {
        bottom: 8px;
        left: 8px;
        right: 8px;
    }
}

/* Print styles */
@media print {
    .resume-actions {
        display: none;
    }
    
    .resume-viewer {
        border: none;
        box-shadow: none;
        height: auto;
    }
    
    .resume-fallback {
        display: none;
    }
}
</style>

---
