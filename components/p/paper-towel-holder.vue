<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hl53vobwk"/><path class="td7zdg99f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:paper-towel-holder" /></template>
<style>
.hl53vobwk {
  d: path("M3.5 5v9m0-4.5h8M7 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

.td7zdg99f {
  d: path("M11.5 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8.5 0V21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
