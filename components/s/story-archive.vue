<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6hf2ow1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:story-archive" /></template>
<style>
.g6hf2ow1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 2.75a8.5 8.5 0 0 1 7 8.25m-6.831 8.357q-.279.056-.56.093t-.565.055t-.567.018q-.284-.001-.567-.021q-.283-.019-.564-.058q-.281-.038-.559-.096q-.278-.057-.552-.133q-.274-.075-.542-.169q-.267-.094-.529-.205q-.261-.111-.514-.24t-.497-.274t-.477-.306t-.456-.337t-.433-.367t-.407-.396q-.197-.204-.38-.421M3 14A8.5 8.5 0 0 1 9.5 2.75m6.625 12h4.25a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-4.25a1.375 1.375 0 0 1-1.375-1.375a1.375 1.375 0 0 1 1.375-1.375M15.5 17.5v4H21v-4");
}

</style>
