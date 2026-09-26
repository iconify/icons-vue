<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dj05c4b-z"/><path class="dgmnhqb1q"/><path class="xcyk673ka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thermometer-sun-sharp-duotone" /></template>
<style>
.dgmnhqb1q {
  d: path("M11.1286 12.4121L10.2144 12.4908C10.1431 12.4969 10.0716 12.5 10 12.5C8.6193 12.5 7.5 11.3807 7.5 10C7.5 8.6193 8.6193 7.5 10 7.5C10.1679 7.5 10.3355 7.5169 10.5 7.5505L11.3 7.7138M5.6967 14.3033L5.4038 14.5962L4.3431 15.6569L4.0503 15.9497M4.5 10L3.5 10L2 10L1 10M5.6967 5.6967L5.4038 5.4038L4.3431 4.3431L4.0503 4.0503M10 4.5L10 3.5L10 2L10 1");
}

.dj05c4b-z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.5 5C13.5 2.7909 15.2909 1 17.5 1C19.7091 1 21.5 2.7909 21.5 5L21.5 13.7251C22.4634 14.7459 23 16.0964 23 17.5C23 20.5376 20.5376 23 17.5 23C14.4624 23 12 20.5376 12 17.5C12 16.0964 12.5366 14.7459 13.5 13.7251L13.5 5Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xcyk673ka {
  fill: currentColor;
  d: path("M19 17.5C19 18.3284 18.3284 19 17.5 19C16.6716 19 16 18.3284 16 17.5C16 16.6716 16.6716 16 17.5 16C18.3284 16 19 16.6716 19 17.5Z");
  stroke: none;
}

</style>
