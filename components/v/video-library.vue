<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jcx262x8m"/><path class="v_pehibsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:video-library" /></template>
<style>
.jcx262x8m {
  d: path("M9.5 2.5h12v19h-12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_pehibsy {
  d: path("m13.5 8.5l5 3.5l-5 3.5ZM3 5.5v16m3.5-18v18");
}

</style>
