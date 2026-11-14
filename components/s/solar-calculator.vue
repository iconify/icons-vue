<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xv8xyjbfn"/><path class="dzx3v1bjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:solar-calculator" /></template>
<style>
.dzx3v1bjx {
  d: path("M7 5.5h7.5v4H7Zm.5 8.5h.01M11 14h.01M7.5 18h.01m8.74 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM18 14.5h.01m-.01 7h.01M14.5 18h.01m6.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xv8xyjbfn {
  d: path("M15.1 21.5H4v-19h13.5v9.2");
}

</style>
