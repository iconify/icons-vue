<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z3nyslhix"/><path class="qcdpe_btd"/><path class="iehj1qwas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:staff-apron" /></template>
<style>
.iehj1qwas {
  d: path("M9.5 14h5v3.5h-5Zm-3-5l-3 3m14-3l3 3");
}

.qcdpe_btd {
  d: path("M6.5 9h11v10.5A1.5 1.5 0 0 1 16 21H8a1.5 1.5 0 0 1-1.5-1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z3nyslhix {
  d: path("M8 3v3a4 4 0 0 0 8 0V3");
}

</style>
