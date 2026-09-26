<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cqmknwfil"/><path clip-rule="evenodd" class="rtfp0_byy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:video-sharp-duotone" /></template>
<style>
.cqmknwfil {
  stroke-opacity: 0.4;
  d: path("M8 5.5C8 6.8807 6.8807 8 5.5 8C4.1193 8 3 6.8807 3 5.5C3 4.1193 4.1193 3 5.5 3C6.8807 3 8 4.1193 8 5.5ZM17 5.5C17 6.8807 15.8807 8 14.5 8C13.1193 8 12 6.8807 12 5.5C12 4.1193 13.1193 3 14.5 3C15.8807 3 17 4.1193 17 5.5Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rtfp0_byy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 11L16 11C16.5523 11 17 11.4477 17 12L17 13.382L21.5528 11.1056C21.6916 11.0361 21.8448 11 22 11C22.5523 11 23 11.4477 23 12L23 21C23 21.5523 22.5523 22 22 22C21.8448 22 21.6916 21.9639 21.5528 21.8944L17 19.618L17 21C17 21.5523 16.5523 22 16 22L2 22C1.4477 22 1 21.5523 1 21L1 12C1 11.4477 1.4477 11 2 11Z");
  stroke: none;
}

</style>
