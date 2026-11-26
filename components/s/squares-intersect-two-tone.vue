<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sm9xu5bhj"/><path class="jicaxfatk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-intersect-two-tone" /></template>
<style>
.jicaxfatk {
  d: path("M11 9L13 9C14.1046 9 15 9.8954 15 11L15 13C15 14.1046 14.1046 15 13 15L11 15C9.8954 15 9 14.1046 9 13L9 11C9 9.8954 9.8954 9 11 9ZM5 15C3.8954 15 3 14.1046 3 13L3 11.5M3 6.5L3 5C3 3.8954 3.8954 3 5 3L6.5 3M11.5 3L13 3C14.1046 3 15 3.8954 15 5M19 9C20.1046 9 21 9.8954 21 11L21 12.5M21 17.5L21 19C21 20.1046 20.1046 21 19 21L17.5 21M12.5 21L11 21C9.8954 21 9 20.1046 9 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sm9xu5bhj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.1213 8.8787C15.6631 9.4205 16 10.1718 16 11L16 13C16 14.6569 14.6569 16 13 16L11 16C9.3431 16 8 14.6569 8 13L8 11C8 9.3431 9.3431 8 11 8L13 8C13.8282 8 14.5795 8.3369 15.1213 8.8787Z");
  stroke: none;
}

</style>
