<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qghqwobfk"/><path class="ttq36q3rp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:skirt-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qghqwobfk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 7.8L5 5C5 3.8954 5.8954 3 7 3L17 3C18.1046 3 19 3.8954 19 5L19 7.8L22.7693 16.8462C22.9218 17.2119 23 17.6042 23 18C23 19.6569 21.6569 21 20 21L12 21L4 21C2.3431 21 1 19.6569 1 18C1 17.6042 1.0782 17.2119 1.2308 16.846Z");
  stroke: none;
}

.ttq36q3rp {
  d: path("M18 8V5C18 4.4477 17.5523 4 17 4H7C6.4477 4 6 4.4477 6 5V8M18 8L21.8462 17.2308C21.9478 17.4745 22 17.736 22 18C22 19.1046 21.1046 20 20 20H15.6667M18 8H14M15.6667 20H8.3333M15.6667 20L14 8M8.3333 20H4C2.8954 20 2 19.1046 2 18C2 17.736 2.0522 17.4745 2.1538 17.2308L6 8M8.3333 20L10 8M6 8H10M10 8H14");
}

</style>
