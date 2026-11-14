<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w7hdekb1e"/><path class="a65mtg04p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:planogram-check" /></template>
<style>
.a65mtg04p {
  d: path("M5 5.5h5v4H5Zm8 0h5v4h-5Zm-8 5.75h5v4H5Zm8.3 4H13v-4h5v4h-2.3M5 17h5v4H5Zm9.5 1l2.5 2.5l4.5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w7hdekb1e {
  d: path("M13.6 21H2.5V3h19v8.8m0 7.9V21h-1.2M2.5 9.5h19m-19 5.75h10.8m2.4 0H18");
}

</style>
