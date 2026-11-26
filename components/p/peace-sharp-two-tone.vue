<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t8drw368i"/><path class="di9wdmb8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:peace-sharp-two-tone" /></template>
<style>
.di9wdmb8j {
  d: path("M19.0711 19.0711L12 12M4.929 19.0711L12 12M12 2L12 12L12 22M19.0711 19.0711C20.8807 17.2614 22 14.7614 22 12C22 6.4772 17.5228 2 12 2C6.4772 2 2 6.4772 2 12C2 14.7614 3.1193 17.2614 4.929 19.0711C6.7386 20.8807 9.2386 22 12 22C14.7614 22 17.2614 20.8807 19.0711 19.0711Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t8drw368i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12Z");
  stroke: none;
}

</style>
