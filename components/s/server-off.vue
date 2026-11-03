<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rc0wevksz"/><path clip-rule="evenodd" class="ne0ewsb8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:server-off" /></template>
<style>
.ne0ewsb8r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 6C13 6.5523 12.5523 7 12 7C11.4477 7 11 6.5523 11 6C11 5.4477 11.4477 5 12 5C12.5523 5 13 5.4477 13 6ZM9 18C9 18.5523 8.5523 19 8 19C7.4477 19 7 18.5523 7 18C7 17.4477 7.4477 17 8 17C8.5523 17 9 17.4477 9 18ZM13 18C13 18.5523 12.5523 19 12 19C11.4477 19 11 18.5523 11 18C11 17.4477 11.4477 17 12 17C12.5523 17 13 17.4477 13 18Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rc0wevksz {
  d: path("M10 10L6 10C4.8954 10 4 9.1046 4 8L4 4M20 20C20 21.1046 19.1046 22 18 22L6 22C4.8954 22 4 21.1046 4 20L4 16C4 14.8954 4.8954 14 6 14L14 14M7.6569 2L18 2C19.1046 2 20 2.8954 20 4L20 8C20 9.1046 19.1046 10 18 10L15.6569 10M2 2L22 22");
}

</style>
