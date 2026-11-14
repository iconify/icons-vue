<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rivajkb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:permission-boundary" /></template>
<style>
.rivajkb_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5v-2A2.5 2.5 0 0 1 5.5 3h2m9 0h2A2.5 2.5 0 0 1 21 5.5v2m0 9v2a2.5 2.5 0 0 1-2.5 2.5h-2m-9 0h-2A2.5 2.5 0 0 1 3 18.5v-2M10.5 3h3m7.5 7.5v3M13.5 21h-3M3 13.5v-3m5 1h8v6H8Zm1.75 0v-2a2.25 2.25 0 0 1 4.5 0v2");
}

</style>
