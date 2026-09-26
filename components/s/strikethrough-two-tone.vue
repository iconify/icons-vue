<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m7jidabhn"/><path class="k7ytdwb6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:strikethrough-two-tone" /></template>
<style>
.k7ytdwb6n {
  d: path("M8 8C8 5.7909 9.7909 4 12 4C13.1093 4 14.1689 4.4607 14.9254 5.272");
}

.m7jidabhn {
  stroke-opacity: 0.4;
  d: path("M12 12C14.2091 12 16 13.7909 16 16C16 18.2091 14.2091 20 12 20C10.3184 20 8.8164 18.9483 8.2412 17.3681M3 12L21 12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
