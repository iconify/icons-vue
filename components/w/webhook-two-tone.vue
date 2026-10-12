<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="dxig4jy0v"/><path class="vx40lcbrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:webhook-two-tone" /></template>
<style>
.dxig4jy0v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M16 5C16 7.2091 14.2091 9 12 9C9.7909 9 8 7.2091 8 5C8 2.7909 9.7909 1 12 1C14.2091 1 16 2.7909 16 5ZM23 19C23 21.2091 21.2091 23 19 23C16.7909 23 15 21.2091 15 19C15 16.7909 16.7909 15 19 15C21.2091 15 23 16.7909 23 19ZM9 19C9 21.2091 7.2091 23 5 23C2.7909 23 1 21.2091 1 19C1 16.7909 2.7909 15 5 15C7.2091 15 9 16.7909 9 19Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vx40lcbrt {
  d: path("M15 5C15 6.6569 13.6569 8 12 8C10.3431 8 9 6.6569 9 5C9 3.3431 10.3431 2 12 2C13.6569 2 15 3.3431 15 5ZM22 19C22 20.6569 20.6569 22 19 22C17.3431 22 16 20.6569 16 19C16 17.3431 17.3431 16 19 16C20.6569 16 22 17.3431 22 19ZM8 19C8 20.6569 6.6569 22 5 22C3.3431 22 2 20.6569 2 19C2 17.3431 3.3431 16 5 16C6.6569 16 8 17.3431 8 19ZM13.3416 7.6833L15.8695 12.739M16 19L12 19M6.3416 16.3167L8.8695 11.261");
}

</style>
