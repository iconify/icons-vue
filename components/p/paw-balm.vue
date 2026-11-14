<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="apt6s_sml"/><path class="n3zrl5mfv"/><path class="o2ly5bbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:paw-balm" /></template>
<style>
.apt6s_sml {
  d: path("M2.5 10a9.5 7.5 0 1 0 19 0a9.5 7.5 0 1 0-19 0Z");
}

.n3zrl5mfv {
  d: path("M2.5 10v3.5a9.5 7.5 0 0 0 19 0V10");
}

.o2ly5bbut {
  d: path("M9 12.75a3 2.25 0 1 0 6 0a3 2.25 0 1 0-6 0Zm-1-4h.01m3.99-2h.01m3.99 2h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
