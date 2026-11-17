<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="aae_hqbif"/><path class="x5vaeebqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sink-sharp-duotone" /></template>
<style>
.aae_hqbif {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 15H21V22C21 22.552 20.552 23 20 23H4C3.448 23 3 22.552 3 22V15H1V13H23V15Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x5vaeebqj {
  d: path("M12 14V5C12 3.343 13.343 2 15 2C16.657 2 18 3.343 18 5V7M16 14V10H21M8 14V10H3");
}

</style>
