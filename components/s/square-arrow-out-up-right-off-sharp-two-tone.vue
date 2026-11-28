<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="utkp3xb7p"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-out-up-right-off-sharp-two-tone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.utkp3xb7p {
  stroke-opacity: 0.4;
  d: path("M7 7L3 7L3 21L17 21L17 17M14.1213 9.8787L14.8284 9.1716L20.8536 3.1464M12 3L21 3L21 12");
}

</style>
