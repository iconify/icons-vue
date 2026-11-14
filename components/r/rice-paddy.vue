<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ko3miyo_i"/><path class="z-mdtq6dp"/><path class="nikg9obct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rice-paddy" /></template>
<style>
.ko3miyo_i {
  d: path("M2.5 19q2.25-1.5 4.75 0T12 19t4.75 0t4.75 0");
}

.nikg9obct {
  d: path("M3.5 7a1.5 3 0 1 0 3 0a1.5 3 0 1 0-3 0Zm14 0a1.5 3 0 1 0 3 0a1.5 3 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z-mdtq6dp {
  d: path("M9.5 21.5V11C9.5 7 8 4 5 4m9.5 17.5V11c0-4 1.5-7 4.5-7");
}

</style>
