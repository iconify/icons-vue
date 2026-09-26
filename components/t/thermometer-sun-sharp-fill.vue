<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i__g5qb9y"/><path class="dgmnhqb1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thermometer-sun-sharp-fill" /></template>
<style>
.dgmnhqb1q {
  d: path("M11.1286 12.4121L10.2144 12.4908C10.1431 12.4969 10.0716 12.5 10 12.5C8.6193 12.5 7.5 11.3807 7.5 10C7.5 8.6193 8.6193 7.5 10 7.5C10.1679 7.5 10.3355 7.5169 10.5 7.5505L11.3 7.7138M5.6967 14.3033L5.4038 14.5962L4.3431 15.6569L4.0503 15.9497M4.5 10L3.5 10L2 10L1 10M5.6967 5.6967L5.4038 5.4038L4.3431 4.3431L4.0503 4.0503M10 4.5L10 3.5L10 2L10 1");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i__g5qb9y {
  fill: currentColor;
  d: path("M13.5 5C13.5 2.7909 15.2909 1 17.5 1C19.7091 1 21.5 2.7909 21.5 5L21.5 13.7251C22.4634 14.7459 23 16.0964 23 17.5C23 20.5376 20.5376 23 17.5 23C14.4624 23 12 20.5376 12 17.5C12 16.0964 12.5366 14.7459 13.5 13.7251L13.5 5ZM18.5 14.1459L18.5 4L16.5 4L16.5 14.1459C15.0167 14.5881 14 15.9522 14 17.5C14 19.433 15.567 21 17.5 21C19.433 21 21 19.433 21 17.5C21 15.9522 19.9833 14.5881 18.5 14.1459ZM19 17.5C19 18.3284 18.3284 19 17.5 19C16.6716 19 16 18.3284 16 17.5C16 16.6716 16.6716 16 17.5 16C18.3284 16 19 16.6716 19 17.5Z");
  stroke: none;
}

</style>
