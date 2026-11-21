<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tcc08jkoy"/><path class="ryh3f4b_f"/><path class="zwcm1lbdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:treasure-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ryh3f4b_f {
  fill: currentColor;
  d: path("M19 3.3417L19 4.1L19 8.0001L19 10L22 10L23 10L23 12L22 12L20.9999 12L19 12L19 20.0001L19 21L17 21L17 20.0001L17 14L17 12L13.9999 12L13.0101 12C13.0068 12.0001 13.0034 12.0001 13 12.0001L10 12.0001L7 12.0001L7 20.0001L7 21L5 21L5 20.0001L5 14L5 12.0001L3 12.0001C2.996 12.0001 2.9921 12 2.9881 12L2 12L1 12L1 11L1 10L2 10L5 10L5 4.1L5 3.3417C5.2593 3.25 5.5268 3.1757 5.8011 3.12C6.1893 3.0412 6.5903 3 7 3L7 4.1L7 8.0001L7 10L9 10C9.004 10 9.008 10 9.012 10.0001L10 10.0001L10.9898 10.0001C10.9932 10 10.9966 10 10.9999 10L13.9999 10L15 10L17 10L17 4.1L17 3C17.4097 3 17.8107 3.0412 18.1989 3.12C18.4732 3.1757 18.7407 3.25 19 3.3417Z");
  stroke: none;
}

.tcc08jkoy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 21L4 21C2.3431 21 1 19.6569 1 18L1 11L1 9C1 6.0961 3.062 3.676 5.8011 3.12C6.1893 3.0412 6.5903 3 7 3L17 3C17.4097 3 17.8107 3.0412 18.1989 3.12C20.938 3.676 23 6.0961 23 9L23 18C23 19.6569 21.6569 21 20 21Z");
  stroke: none;
}

.zwcm1lbdi {
  d: path("M10 11V9H14V11M10 11V13C10 14.1046 10.8954 15 12 15C13.1046 15 14 14.1046 14 13V11");
}

</style>
