<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wvzbsvdug"/><path class="z8an_mbar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-out-down-right-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wvzbsvdug {
  stroke-opacity: 0.4;
  d: path("M10 17L3 17L3 3L17 3L17 10");
}

.z8an_mbar {
  d: path("M12.7071 12.7071L20.8536 20.8536M12 21L21 21L21 12");
}

</style>
