<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t7mqi5p0u"/><path class="r0sazqbgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:server-zap" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r0sazqbgm {
  fill: currentColor;
  d: path("M8 6C8 6.5523 7.5523 7 7 7C6.4477 7 6 6.5523 6 6C6 5.4477 6.4477 5 7 5C7.5523 5 8 5.4477 8 6ZM12 6C12 6.5523 11.5523 7 11 7C10.4477 7 10 6.5523 10 6C10 5.4477 10.4477 5 11 5C11.5523 5 12 5.4477 12 6ZM8 18C8 18.5523 7.5523 19 7 19C6.4477 19 6 18.5523 6 18C6 17.4477 6.4477 17 7 17C7.5523 17 8 17.4477 8 18ZM12 18C12 18.5523 11.5523 19 11 19C10.4477 19 10 18.5523 10 18C10 17.4477 10.4477 17 11 17C11.5523 17 12 17.4477 12 18Z");
  stroke: none;
}

.t7mqi5p0u {
  d: path("M5 2L17 2C18.1046 2 19 2.8954 19 4L19 8C19 9.1046 18.1046 10 17 10L5 10C3.8954 10 3 9.1046 3 8L3 4C3 2.8954 3.8954 2 5 2ZM13 22L5 22C3.8954 22 3 21.1046 3 20L3 16C3 14.8954 3.8954 14 5 14L13 14M20 16L17 19L21 19L18 22");
}

</style>
