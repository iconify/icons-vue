<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGzlAJVIul)" class="w7hv7y7ul"/><path fill="url(#SVGju7VWdKa)" class="yf3ysxx2f"/><path fill="url(#SVGThnOcctX)" class="mxbw2-h-k"/><path fill="url(#SVG9ypHebfn)" class="ez1etzb1f"/><defs><linearGradient id="SVGzlAJVIul" x1="11.997" x2="11.997" y1="3" y2="21.007" gradientUnits="userSpaceOnUse"><stop class="b_fvvlz7a"/><stop offset="1" class="rano1jbzh"/></linearGradient><linearGradient id="SVGju7VWdKa" x1="11.997" x2="11.997" y1="3.001" y2="20.938" gradientUnits="userSpaceOnUse"><stop class="dtcgcg9vz"/><stop offset=".7" class="w7rj_bcgn"/></linearGradient><linearGradient id="SVGThnOcctX" x1="13.336" x2="10.857" y1="12.947" y2="21.729" gradientUnits="userSpaceOnUse"><stop class="s48hmmbov"/><stop offset=".56" class="n3efd8cmk"/></linearGradient><linearGradient id="SVG9ypHebfn" x1="8.517" x2="9.318" y1="7.716" y2="11.582" gradientUnits="userSpaceOnUse"><stop class="mz7dz8bnk"/><stop offset=".61" class="ya1zc1ykq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stsol" /></template>
<style>
.b_fvvlz7a {
  stop-color: var(--svg-color--498be9, #498be9);
}

.dtcgcg9vz {
  stop-color: var(--svg-color--4a8cea, #4a8cea);
}

.ez1etzb1f {
  d: path("M11.998 3v9.502l-4.416-2.6z");
}

.ft5dv1b6b {
  fill: none;
}

.mxbw2-h-k {
  d: path("m11.997 3l4.426 6.901l-4.426 2.601z");
}

.mz7dz8bnk {
  stop-color: var(--svg-color--ffe235, #ffe235);
}

.n3efd8cmk {
  stop-color: var(--svg-color--568fdd, #568fdd);
}

.rano1jbzh {
  stop-color: var(--svg-color--56f2ff, #56f2ff);
}

.s48hmmbov {
  stop-color: var(--svg-color--fb8174, #fb8174);
}

.w7hv7y7ul {
  d: path("m11.997 14.102l-5.126-3.01l-.145.22a6.34 6.34 0 0 0 .85 7.846a6.23 6.23 0 0 0 6.816 1.363a6.2 6.2 0 0 0 2.026-1.363a6.32 6.32 0 0 0 .85-7.846l-.145-.22z");
}

.w7rj_bcgn {
  stop-color: var(--svg-color--5abef4, #5abef4);
}

.ya1zc1ykq {
  stop-color: var(--svg-color--5dcba2, #5dcba2);
}

.yf3ysxx2f {
  d: path("m17.123 11.103l-5.126 3.01l-5.131-3.015l5.146-2.69z");
}

</style>
