<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qkqg6zbpv"/><path class="gwis2wb-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sprouts-jar" /></template>
<style>
.gwis2wb-v {
  d: path("M12 12.75c0-2-1.5-3-3.25-3c0 2 1.5 3 3.25 3Zm0 0c0-2 1.5-3 3.25-3c0 2-1.5 3-3.25 3Z");
}

.qkqg6zbpv {
  d: path("M7 7h10c1 1 1.5 2.5 1.5 4v7a2.5 2.5 0 0 1-2.5 2.5H8A2.5 2.5 0 0 1 5.5 18v-7c0-1.5.5-3 1.5-4Zm-.5-3.5h11M12 17.75v-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
