<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kqqv5kb9t"/><path class="rlr2al09o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paper-bag-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kqqv5kb9t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 21L2 3C2 2.4477 2.4477 2 3 2L4 2C4.7573 2 5.4942 2.2456 6.1 2.7C6.3596 2.8947 6.6754 3 7 3C7.3246 3 7.6404 2.8947 7.9 2.7C8.5058 2.2456 9.2427 2 10 2C10.7573 2 11.4942 2.2456 12.1 2.7C12.3596 2.8947 12.6754 3 13 3C13.3246 3 13.6404 2.8947 13.9 2.7C14.5058 2.2456 15.2427 2 16 2L17 2C17.4687 2 17.8745 2.3255 17.9762 2.7831L21.9762 20.7831C21.992 20.8543 22 20.927 22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21Z");
  stroke: none;
}

.rlr2al09o {
  d: path("M3 21L3 3L4 3C4.5409 3 5.0673 3.1754 5.5 3.5C5.9327 3.8246 6.4591 4 7 4C7.5409 4 8.0673 3.8246 8.5 3.5C8.9327 3.1754 9.4591 3 10 3C10.5409 3 11.0673 3.1754 11.5 3.5C11.9327 3.8246 12.4591 4 13 4C13.5409 4 14.0673 3.8246 14.5 3.5C14.9327 3.1754 15.4591 3 16 3L17 3L21 21L3 21ZM17 3L17 21M7 8L13 8");
}

</style>
