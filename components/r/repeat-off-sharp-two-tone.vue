<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="hduwpi77y"/><path class="em89il-fx"/><path class="hpn4nrgbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:repeat-off-sharp-two-tone" /></template>
<style>
.em89il-fx {
  stroke-opacity: 0.4;
  d: path("M3 13L3 6L6 6");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hduwpi77y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M18.5858 7L10.6569 7L10.6569 5L18.5858 5L17 3.4142L18.4142 2L21.7071 5.2929C21.8946 5.4804 22 5.7348 22 6C22 6.2652 21.8946 6.5196 21.7071 6.7071L18.4142 10L17 8.5858L18.5858 7ZM22 11L22 16.3431L20 16.3431L20 11L22 11Z");
  stroke: none;
}

.hpn4nrgbp {
  d: path("M18 18L3 18M6.2929 21.2929L3 18L6.2929 14.7071M1.7071 1.7071L22.2929 22.2929");
}

</style>
