<style>

    :global(*) {
        margin: 0;
    }

    :global(html, body) {
        height: 100%;
    }

    :global(*, *::before, *::after) {
        box-sizing: border-box;
    }

    :global(body) {
        line-height: 1.5;
        -webkit-font-smoothing: antialiased;
    }

    :global(img, picture, video, canvas, svg) {
        display: block;
        max-width: 100%;
    }

    :global(input, button, textarea, select) {
        font: inherit;
    }

    :global(p, h1, h2, h3, h4, h5, h6) {
        overflow-wrap: break-word;
    }

    :global(#app){
        isolation: isolate;
    }
</style>