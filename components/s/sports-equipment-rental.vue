<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y5gbktdwf"/><path class="fra41bbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sports-equipment-rental" /></template>
<style>
.fra41bbpn {
  d: path("M16.25 9.5c-.5-1-1.5-1.25-2.25-1.25c-1.25 0-2.25.75-2.25 2c0 2.5 4.5 1.25 4.5 3.75c0 1.25-1 1.75-2.25 1.75c-1 0-2-.5-2.25-1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y5gbktdwf {
  d: path("M8.5 4.5h11v15h-11l-5-7.5ZM8.25 12h.01M14 7.25v9.5");
}

</style>
