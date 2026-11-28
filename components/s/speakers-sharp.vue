<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pbijtdbju"/><path clip-rule="evenodd" class="u4m5zg8vx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:speakers-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pbijtdbju {
  d: path("M5 4H2V20H5M8 2H22V22H8V2ZM18 15C18 16.657 16.657 18 15 18C13.343 18 12 16.657 12 15C12 13.343 13.343 12 15 12C16.657 12 18 13.343 18 15Z");
}

.u4m5zg8vx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 7C16.5 7.828 15.828 8.5 15 8.5C14.172 8.5 13.5 7.828 13.5 7C13.5 6.172 14.172 5.5 15 5.5C15.828 5.5 16.5 6.172 16.5 7Z");
  stroke: none;
}

</style>
