<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pejqwlblo"/><path class="c9u1k203l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticker-sharp-two-tone" /></template>
<style>
.c9u1k203l {
  d: path("M22 12C22 6.4772 17.5228 2 12 2C6.4772 2 2 6.4772 2 12C2 17.5228 6.4772 22 12 22ZM22 12C21.3475 11.8374 20.6776 11.7552 20.0052 11.7552C15.4489 11.7552 11.7552 15.4489 11.7552 20.0052C11.7552 20.6776 11.8374 21.3475 12 22M22 12L12 22");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pejqwlblo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 5.9249 18.0751 1 12 1C5.9249 1 1 5.9249 1 12C1 18.0751 5.9249 23 12 23C12.2652 23 12.5196 22.8946 12.7071 22.7071L22.7071 12.7071C22.8946 12.5196 23 12.2652 23 12Z");
  stroke: none;
}

</style>
