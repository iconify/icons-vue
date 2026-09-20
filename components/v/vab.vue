<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG6nFEBdpm)" class="sbxki-brd"/><defs><linearGradient id="SVG6nFEBdpm" x1="5.384" x2="12.518" y1="5.914" y2="19.151" gradientUnits="userSpaceOnUse"><stop class="bqbum-ggb"/><stop offset=".82" class="ch02ot2zw"/><stop offset="1" class="sydswib2t"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vab" /></template>
<style>
.bqbum-ggb {
  stop-color: var(--svg-color--470180, #470180);
}

.ch02ot2zw {
  stop-color: var(--svg-color--ef62c9, #ef62c9);
}

.ft5dv1b6b {
  fill: none;
}

.sbxki-brd {
  d: path("M13.233 19.463a1.006 1.006 0 0 1-1.71 0L3.134 5.49c-.381-.635.095-1.429.858-1.429h15.026c1.535 0 2.482 1.604 1.704 2.869l-1.826 2.98c-.709 1.159-1.932 1.561-3.334 1.561H9.85a.52.52 0 0 0-.498.53c.01.317.265.529.498.529h4.144a1.927 1.927 0 0 1 1.64 2.927z");
}

.sydswib2t {
  stop-color: var(--svg-color--ffccf7, #ffccf7);
}

</style>
