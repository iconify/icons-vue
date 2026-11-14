<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vi-y5jnwu"/><path class="hprge7mgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:settings-wrench" /></template>
<style>
.hprge7mgu {
  d: path("M15.5 3.75V7A1.5 1.5 0 0 0 17 8.5h3.25M4.5 19.5L12 12m5.692 4.579l.027-1.032h1.062l.027 1.032l.826.477l.907-.492l.532.92l-.881.539v.954l.881.539l-.532.92l-.907-.492l-.826.477l-.027 1.032h-1.062l-.027-1.032l-.826-.477l-.907.492l-.532-.92l.881-.539v-.954l-.881-.539l.532-.92l.907.492Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vi-y5jnwu {
  d: path("M20.25 8.5a4.75 4.75 0 1 1-4.75-4.75");
}

</style>
