<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o96v_vbje"/><path class="yb_4zs5qh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:separator-horizontal-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o96v_vbje {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2L17 2C18.6569 2 20 3.3431 20 5L20 6C20 7.6569 18.6569 9 17 9L7 9C5.3431 9 4 7.6569 4 6L4 5C4 3.3431 5.3431 2 7 2ZM12 15L17 15C18.6569 15 20 16.3431 20 18L20 19C20 20.6569 18.6569 22 17 22L7 22C5.3431 22 4 20.6569 4 19L4 18C4 16.3431 5.3431 15 7 15Z");
  stroke: none;
}

.yb_4zs5qh {
  d: path("M7 3L17 3C18.1046 3 19 3.8954 19 5L19 6C19 7.1046 18.1046 8 17 8L7 8C5.8954 8 5 7.1046 5 6L5 5C5 3.8954 5.8954 3 7 3ZM3 12H21M7 16L17 16C18.1046 16 19 16.8954 19 18L19 19C19 20.1046 18.1046 21 17 21L7 21C5.8954 21 5 20.1046 5 19L5 18C5 16.8954 5.8954 16 7 16Z");
}

</style>
