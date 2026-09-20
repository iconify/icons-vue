<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path clip-rule="evenodd" class="om8aqlbre"/><path class="uu6t-3fyh"/><path class="e0utowb9x"/><path class="vuybsn3is"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pancake-swap-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.e0utowb9x {
  fill: var(--svg-color--fedc90, #fedc90);
  d: path("M12.005 18.32c-3.346 0-7.029-1.791-7.035-4.11v.01c0 2.871 2.474 5.035 7.035 5.035c4.562 0 7.035-2.164 7.035-5.034v-.01c-.005 2.318-3.688 4.11-7.035 4.11");
}

.ft5dv1b6b {
  fill: none;
}

.om8aqlbre {
  fill: var(--svg-color--633001, #633001);
  fill-rule: evenodd;
  d: path("M11.994 20c-2.376-.002-4.29-.566-5.627-1.58c-1.353-1.026-2.07-2.481-2.07-4.129c0-1.587.715-2.731 1.526-3.505a6.7 6.7 0 0 1 1.824-1.218c-.11-.335-.248-.774-.371-1.227c-.165-.607-.327-1.319-.327-1.84c0-.618.136-1.238.503-1.72c.387-.508.97-.781 1.672-.781a1.95 1.95 0 0 1 1.378.549c.348.332.58.772.74 1.232c.282.808.391 1.822.422 2.835h.672c.03-1.013.14-2.027.421-2.835c.16-.46.392-.9.74-1.232A1.95 1.95 0 0 1 14.877 4c.701 0 1.284.273 1.672.782c.367.481.503 1.101.503 1.719c0 .521-.162 1.233-.327 1.84c-.123.453-.261.892-.371 1.227a6.7 6.7 0 0 1 1.824 1.218c.81.774 1.527 1.918 1.527 3.505c0 1.648-.718 3.104-2.071 4.13c-1.338 1.013-3.251 1.577-5.627 1.579z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uu6t-3fyh {
  fill: var(--svg-color--d1884f, #d1884f);
  d: path("M9.124 4.587c-1.028 0-1.5.767-1.5 1.827c0 .843.549 2.53.774 3.187a.295.295 0 0 1-.174.367c-.823.325-3.254 1.514-3.254 4.237c0 2.868 2.47 5.03 7.024 5.034h.011c4.555-.004 7.024-2.166 7.024-5.034c0-2.723-2.43-3.912-3.253-4.237a.295.295 0 0 1-.175-.367c.226-.657.775-2.344.775-3.187c0-1.06-.473-1.827-1.5-1.827c-1.48 0-1.848 2.095-1.874 4.344a.274.274 0 0 1-.274.272h-1.457a.274.274 0 0 1-.273-.272c-.026-2.249-.395-4.344-1.874-4.344");
}

.vuybsn3is {
  fill: var(--svg-color--633001, #633001);
  d: path("M10.146 13.498c0 .783-.37 1.19-.826 1.19c-.457 0-.827-.407-.827-1.19s.37-1.19.827-1.19s.826.407.826 1.19m5.371 0c0 .783-.37 1.19-.826 1.19s-.826-.407-.826-1.19s.37-1.19.826-1.19s.826.407.826 1.19");
}

</style>
