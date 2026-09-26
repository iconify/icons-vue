<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dciw6mb9j"/><path class="gjd67cccr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wifi-info-fill" /></template>
<style>
.dciw6mb9j {
  d: path("M9.3333 15.0186C10.0667 14.3626 11.0161 14 12 14C12.2451 14 12.4898 14.0225 12.7308 14.0673M6.6667 12.0372C8.1334 10.7253 10.0322 10 12 10C12.4903 10 12.9795 10.0451 13.4616 10.1346M4 9.0557C6.2001 7.0879 9.0483 6 12 6C14.9517 6 17.7999 7.0879 20 9.0557M17 16V18");
}

.gjd67cccr {
  fill: currentColor;
  d: path("M13 18C13 18.5523 12.5523 19 12 19C11.4477 19 11 18.5523 11 18C11 17.4477 11.4477 17 12 17C12.5523 17 13 17.4477 13 18ZM18 12C18 12.5523 17.5523 13 17 13C16.4477 13 16 12.5523 16 12C16 11.4477 16.4477 11 17 11C17.5523 11 18 11.4477 18 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
