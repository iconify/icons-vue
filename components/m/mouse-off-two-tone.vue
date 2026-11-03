<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="tx1w06y7h"/><path class="tycygtbpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse-off-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tx1w06y7h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M18.2181 18.2181C17.0152 20.5419 14.6167 22.0007 12 22C8.134 22 5 18.866 5 15L5 9C4.9983 7.8801 5.2665 6.7762 5.7819 5.7819L18.2181 18.2181ZM8.8472 2.7485C9.8248 2.2555 10.9045 1.9986 11.9995 1.9986C15.8661 1.9986 19.0005 5.1334 19 9L19 12.3431L18.98 12.3431C18.9802 12.8844 18.5415 13.3233 18.0002 13.3233C17.7402 13.3233 17.4908 13.22 17.3071 13.0361L17.2929 13.0503L8.5911 4.3484L8.6052 4.3343C8.4214 4.1505 8.3181 3.9011 8.3181 3.6412C8.3181 3.2714 8.5262 2.9331 8.8562 2.7664L8.8472 2.7485Z");
  stroke: none;
}

.tycygtbpj {
  d: path("M17.4697 17.4697C16.5283 19.5515 14.4333 21 12 21C8.6863 21 6 18.3137 6 15L6 9C6 8.1196 6.1896 7.2835 6.5303 6.5303M2 2L22 22");
}

</style>
