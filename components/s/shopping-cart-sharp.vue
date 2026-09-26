<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ivbuyeg9r"/><path class="czbbm17fv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-cart-sharp" /></template>
<style>
.czbbm17fv {
  fill: currentColor;
  d: path("M10.5 20.5C10.5 21.3284 9.8284 22 9 22C8.1716 22 7.5 21.3284 7.5 20.5C7.5 19.6716 8.1716 19 9 19C9.8284 19 10.5 19.6716 10.5 20.5ZM18.5 20.5C18.5 21.3284 17.8284 22 17 22C16.1716 22 15.5 21.3284 15.5 20.5C15.5 19.6716 16.1716 19 17 19C17.8284 19 18.5 19.6716 18.5 20.5Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ivbuyeg9r {
  d: path("M1 3L4 3L5 7M5 7L21.9989 7L18.9999 15L7 15L5 7Z");
}

</style>
