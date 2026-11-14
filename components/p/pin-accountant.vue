<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lv6vspbia"/><path class="olz4_v9jp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-accountant" /></template>
<style>
.lv6vspbia {
  d: path("M13.6 19.5H4v-17h12v7.2");
}

.olz4_v9jp {
  d: path("M6.75 5.25h6.5v3.5h-6.5Zm1.25 7h.01m3.99 0h.01m-4.01 4h.01m3.99 0h.01M18 21l-2.25-3.25a3.25 3.25 0 1 1 4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
