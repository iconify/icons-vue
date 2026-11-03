<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jlfqcbdph"/><path class="f8v3wib_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-fast-two-tone" /></template>
<style>
.f8v3wib_k {
  d: path("M14 18L14 7C14 5.34315 12.6569 4 11 4L2 4M2 8L8 8M2 12L5 12M2 16L2 17C2 17.5523 2.44772 18 3 18L4 18M10 18L14 18M20 18L21 18C21.5523 18 22 17.5523 22 17L22 13C22 12.4696 21.7893 11.9609 21.4142 11.5858L18.4142 8.58579C18.0391 8.21071 17.5304 8 17 8L14 8M9 18C9 19.1046 8.1046 20 7 20C5.8954 20 5 19.1046 5 18C5 16.8954 5.8954 16 7 16C8.1046 16 9 16.8954 9 18ZM19 18C19 19.1046 18.1046 20 17 20C15.8954 20 15 19.1046 15 18C15 16.8954 15.8954 16 17 16C18.1046 16 19 16.8954 19 18Z");
}

.jlfqcbdph {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3L11 3C13.2091 3 15 4.7909 15 7L16.5858 7C17.1162 7 17.6249 7.2107 18 7.5858L22.4142 12C22.7893 12.3751 23 12.8838 23 13.4142L23 17C23 18.1046 22.1046 19 21 19L3 19C1.8954 19 1 18.1046 1 17L1 16.0001L1.01 16.0001C1.01 15.4533 1.4533 15.0101 2 15.0101C2.5468 15.0101 2.99 15.4533 2.99 16.0001L3 16.0001L3 15.0001L3 15L3 4L1 4C1.0001 3.4477 1.4478 3 2 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
