<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bhs8rm6xm"/><path class="qg9qewbnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:variable-square-broken" /></template>
<style>
.bhs8rm6xm {
  d: path("M17 7.99991C14 8.99991 12 11.9999 12 11.9999M12 11.9999C12 11.9999 10 14.9999 7 15.9999M12 11.9999C12 11.9999 11 6.99991 9 7.99991M12 11.9999C12 11.9999 13 16.9999 15 15.9999");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qg9qewbnt {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.286 22 4.9289 22 3.4645 20.5355C2 19.0711 2 16.714 2 12C2 7.286 2 4.9289 3.4645 3.4645C4.9289 2 7.286 2 12 2C16.714 2 19.0711 2 20.5355 3.4645C21.5093 4.4382 21.8356 5.8066 21.9449 8");
}

</style>
