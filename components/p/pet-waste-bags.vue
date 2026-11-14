<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="asyd-ackt"/><path class="u5sg0taud"/><path class="u7lguny_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-waste-bags" /></template>
<style>
.asyd-ackt {
  d: path("M4.5 2.5h15V10h-15ZM7 10v10.5l2.5 1l2.5-1l2.5 1l2.5-1V10");
}

.u5sg0taud {
  fill: currentColor;
  d: path("M10.25 16.25a1.75 1.25 0 1 0 3.5 0a1.75 1.25 0 1 0-3.5 0Z");
}

.u7lguny_r {
  d: path("M10 13.5h.01M12 13h.01m1.99.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
