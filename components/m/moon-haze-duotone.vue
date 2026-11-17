<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lm0ke8_gk"/><path class="xqavz_biw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-haze-duotone" /></template>
<style>
.lm0ke8_gk {
  stroke-opacity: 0.4;
  d: path("M18.3264 13C18.7583 12.091 19 11.074 19 10C17.0185 11.585 14.1618 11.427 12.3673 9.633C10.5729 7.838 10.4147 4.982 12 3C8.134 3 5 6.134 5 10C5 11.074 5.2417 12.091 5.6736 13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xqavz_biw {
  d: path("M4 17H20M5 21H10M14 21H19");
}

</style>
