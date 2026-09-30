<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ewt0tn85d"/><path class="erqvv3bpq"/><path class="fywt03itq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:money-bag-minus-sharp-duotone" /></template>
<style>
.erqvv3bpq {
  fill: currentColor;
  d: path("M9.2474 7.6585L5.7474 3.6585C5.5879 3.4762 5.4999 3.2422 5.4999 2.9999C5.4999 2.4477 5.9476 2 6.4999 2C6.6165 2 6.7322 2.0204 6.8417 2.0602L12 3.9359L17.1583 2.0602C17.2678 2.0204 17.3835 2 17.5001 2C18.0524 2 18.5001 2.4477 18.5001 2.9999C18.5001 3.2422 18.4121 3.4762 18.2526 3.6585L14.7526 7.6585C14.5627 7.8755 14.2884 8 14 8L10 8C9.7116 8 9.4373 7.8755 9.2474 7.6585Z");
  stroke: none;
}

.ewt0tn85d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.2133 6.4767L5.7474 3.6585C5.5879 3.4762 5.4999 3.2422 5.4999 2.9999C5.4999 2.4477 5.9476 2 6.4999 2C6.6165 2 6.7322 2.0204 6.8417 2.0602L12 3.9359L17.1583 2.0602C17.2678 2.0204 17.3835 2 17.5001 2C18.0524 2 18.5001 2.4477 18.5001 2.9999C18.5001 3.2422 18.4121 3.4762 18.2526 3.6585L15.7867 6.4767C19.4921 7.6833 22 11.1375 22 15.0344L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 15.0344C2 11.1375 4.5079 7.6833 8.2133 6.4767Z");
  stroke: none;
}

.fywt03itq {
  d: path("M8 14L16 14");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
