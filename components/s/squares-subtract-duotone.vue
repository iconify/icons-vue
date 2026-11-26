<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gm-by9bsw"/><path clip-rule="evenodd" class="cnqnm5bcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-subtract-duotone" /></template>
<style>
.cnqnm5bcp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2L13 2C14.6569 2 16 3.3431 16 5L16 7C16 8.6569 14.6569 10 13 10L10 10L10 13C10 14.6569 8.6569 16 7 16L5 16C3.3431 16 2 14.6569 2 13L2 5C2 3.3431 3.3431 2 5 2Z");
  stroke: none;
}

.gm-by9bsw {
  stroke-opacity: 0.4;
  d: path("M19 9C20.1046 9 21 9.8954 21 11L21 12.5M21 17.5L21 19C21 20.1046 20.1046 21 19 21L17.5 21M12.5 21L11 21C9.8954 21 9 20.1046 9 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
