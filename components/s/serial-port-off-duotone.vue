<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xkushsbuq"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:serial-port-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xkushsbuq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.7872 18.787C18.3806 18.926 17.9467 19 17.4987 19H6.5013C4.6658 19 3.066 17.751 2.6208 15.97L1.1208 9.97C0.4897 7.446 2.3984 5.001 5 5L18.7872 18.787ZM19.8971 15.654L10.9498 6.707C10.7688 6.526 10.6569 6.276 10.6569 6C10.6569 5.448 11.1046 5 11.6569 5H12H18.9987C21.601 5 23.5104 7.446 22.8792 9.97L21.5681 15.215C21.4511 15.637 21.0639 15.947 20.6042 15.947C20.3281 15.947 20.0781 15.835 19.8971 15.654ZM17 10C17 9.448 16.5523 9 16 9C15.4477 9 15 9.448 15 10C15 10.552 15.4477 11 16 11C16.5523 11 17 10.552 17 10Z");
  stroke: none;
}

</style>
