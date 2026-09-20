<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGeuDfoeYL)" class="swx88_buk"/><defs><linearGradient id="SVGeuDfoeYL" x1="19.619" x2="9.3" y1="7.171" y2="16.838" gradientUnits="userSpaceOnUse"><stop class="u9q0gsbru"/><stop offset=".28" class="ivgo_nzpj"/><stop offset=".57" class="m5_qrb4tl"/><stop offset="1" class="y0atxvdoq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vai" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ivgo_nzpj {
  stop-color: var(--svg-color--5d70f8, #5d70f8);
}

.m5_qrb4tl {
  stop-color: var(--svg-color--5f5bf6, #5f5bf6);
}

.swx88_buk {
  d: path("m7.522 5.582l3.884 3.799a.36.36 0 0 1 0 .513L7.518 13.7a.38.38 0 0 1-.527 0L3.107 9.898a.36.36 0 0 1 0-.513l3.889-3.803a.38.38 0 0 1 .526 0m4.743 4.717L16.15 14.1a.36.36 0 0 1 0 .513l-3.888 3.803a.38.38 0 0 1-.526 0L7.85 14.62a.36.36 0 0 1 0-.513l3.888-3.807a.38.38 0 0 1 .526 0m4.744-4.717l3.883 3.799a.36.36 0 0 1 0 .513L17.005 13.7a.38.38 0 0 1-.526 0l-3.884-3.803a.36.36 0 0 1 0-.513l3.888-3.803a.38.38 0 0 1 .527 0");
}

.u9q0gsbru {
  stop-color: var(--svg-color--5c84f9, #5c84f9);
}

.y0atxvdoq {
  stop-color: var(--svg-color--6349f4, #6349f4);
}

</style>
