<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qnp16mpmi"/><path class="qlydgsszt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:puzzle-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qlydgsszt {
  d: path("M7 6L7 7L3 7L3 11L4 11C5.6569 11 7 12.3431 7 14C7 15.6569 5.6569 17 4 17L3 17L3 21L17 21L17 17L18 17C19.6569 17 21 15.6569 21 14C21 12.3431 19.6569 11 18 11L17 11L17 7L13 7L13 6C13 4.3431 11.6569 3 10 3C8.3431 3 7 4.3431 7 6Z");
}

.qnp16mpmi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 2C12.2092 2 14 3.79082 14 6H17C17.5523 6 18 6.44772 18 7V10C20.2092 10 22 11.7908 22 14C22 16.2092 20.2092 18 18 18V21C18 21.5523 17.5523 22 17 22H3C2.44772 22 2 21.5523 2 21V17C2 16.4477 2.44772 16 3 16H4C5.10462 16 6 15.1046 6 14C6 12.8954 5.10462 12 4 12H3C2.44772 12 2 11.5523 2 11V7C2 6.44772 2.44772 6 3 6H6C6 3.79082 7.79082 2 10 2Z");
  stroke: none;
}

</style>
