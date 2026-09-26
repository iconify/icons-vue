<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sczqjlb6f"/><path class="t3v7rmpwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stop-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sczqjlb6f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7C4 5.343146 5.343146 4 7 4L17 4C18.656854 4 20 5.343146 20 7L20 17C20 18.656854 18.656854 20 17 20L7 20C5.343146 20 4 18.656854 4 17Z");
  stroke: none;
}

.t3v7rmpwv {
  d: path("M5 7C5 5.895431 5.895431 5 7 5L17 5C18.104569 5 19 5.895431 19 7L19 17C19 18.104569 18.104569 19 17 19L7 19C5.895431 19 5 18.104569 5 17Z");
}

</style>
