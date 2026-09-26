<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="db-zerbsw"/><path class="kzp4b4bbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-pen-sharp-fill" /></template>
<style>
.db-zerbsw {
  fill: currentColor;
  d: path("M10.8714 14.4285L14.9962 12.7786C15.1219 12.7283 15.2361 12.653 15.3319 12.5572L21.1945 6.6945C22.1709 5.7183 22.1709 3.7817 21.1945 2.8054C20.2183 1.8291 18.2817 1.8291 17.3054 2.8055L11.4428 8.6681C11.347 8.7639 11.2717 8.8781 11.2214 9.0038L9.5715 13.1286C9.245 13.9449 10.0551 14.755 10.8714 14.4285Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kzp4b4bbd {
  d: path("M13 3L3 3L3 21L21 21L21 11");
}

</style>
