<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l__qtsvwl"/><path class="xjgeo2bxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l__qtsvwl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1.7163 6.9585L21.7163 1.0411C21.8084 1.0138 21.9039 1 22 1C22.5523 1 23 1.4477 23 2C23 2.0961 22.9862 2.1916 22.9589 2.2837L17.0415 22.2837C16.9158 22.7085 16.5256 23 16.0826 23C15.7522 23 15.443 22.8368 15.2567 22.5638L9.6495 14.3505L1.4362 8.7433C1.1632 8.557 1 8.2478 1 7.9174C1 7.4744 1.2915 7.0842 1.7163 6.9585Z");
  stroke: none;
}

.xjgeo2bxv {
  d: path("M2 7.9174L22 2L16.0826 22L10.369 13.631L2 7.9174ZM10.369 13.631L22 2");
}

</style>
