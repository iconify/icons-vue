<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pel4bdbze"/><path class="s-xpk0xxq"/><path class="axh_y-hbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tube-diagonal-sharp-duotone" /></template>
<style>
.axh_y-hbe {
  d: path("M13.0471 1.838L20.4544 6.661");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pel4bdbze {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.6796 1.7076L19.7076 4.9815C19.991 5.1661 20.162 5.4814 20.162 5.8195C20.162 6.0133 20.1057 6.2028 20 6.3652L10.3521 21.1826C9.6139 22.3162 8.3528 23 7 23C4.7909 23 3 21.2091 3 19C3 18.2251 3.2251 17.4668 3.6479 16.8174L13.2959 2C13.4804 1.7166 13.7957 1.5456 14.1339 1.5456C14.3276 1.5456 14.5172 1.6019 14.6796 1.7076Z");
  stroke: none;
}

.s-xpk0xxq {
  fill: currentColor;
  d: path("M6.7847 12L16.331 12L10.3521 21.1826C9.6139 22.3162 8.3528 23 7 23C4.7909 23 3 21.2091 3 19C3 18.2251 3.2251 17.4668 3.6479 16.8174Z");
  stroke: none;
}

</style>
