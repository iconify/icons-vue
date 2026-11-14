<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ks9teom-y"/><path class="rbwedcb5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:single-point-mooring" /></template>
<style>
.ks9teom-y {
  d: path("M7 8.25a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.rbwedcb5p {
  d: path("M2.5 11.75q1.75-1.5 3.5 0q1.25 1 2.5 0m7 0q1.25-1 2.5 0q1.75 1.5 3.5 0m-9.5 1.5V15m0 2.5V19m0 2.25v.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
