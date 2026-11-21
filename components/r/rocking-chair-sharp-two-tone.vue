<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="q0wlnrb7r"/><path class="o8_3_293y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rocking-chair-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8_3_293y {
  stroke-opacity: 0.4;
  d: path("M22.3103 16.7044L22 17C20.5505 18.3805 18.8454 19.4327 17 20.1107C15.4127 20.6938 13.7216 21 12 21C10.2784 21 8.5873 20.6938 7 20.1107C5.1546 19.4327 3.4495 18.3805 2 17L1.6897 16.7044");
}

.q0wlnrb7r {
  d: path("M14 13L17 20.1107M10 13L7 20.1107M18 13L17 13L14 13L10 13L7 13L4 3L3.7862 2.2873");
}

</style>
