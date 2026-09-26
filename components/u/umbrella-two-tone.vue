<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h3kcgv4vg"/><path class="y0hjv5blu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:umbrella-two-tone" /></template>
<style>
.h3kcgv4vg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12C23 13.0047 21.6845 13.382 21.152 12.53C20.2937 11.1567 18.7063 11.1567 17.848 12.53C17.4563 13.1567 16.5437 13.1567 16.152 12.53C15.2937 11.1567 13.7063 11.1567 12.848 12.53C12.4563 13.1567 11.5437 13.1567 11.152 12.53C10.2937 11.1567 8.7063 11.1567 7.848 12.53C7.4563 13.1567 6.5437 13.1567 6.152 12.53C5.2937 11.1567 3.7063 11.1567 2.848 12.53C2.3155 13.382 1 13.0047 1 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y0hjv5blu {
  d: path("M2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12C20.75 10 18.25 10 17 12C15.75 10 13.25 10 12 12C10.75 10 8.25 10 7 12C5.75 10 3.25 10 2 12ZM12 12V19C12 20.6569 13.3431 22 15 22C16.6569 22 18 20.6569 18 19");
}

</style>
