<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zyz40f3pg"/><path class="pnav-achm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wallet-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pnav-achm {
  d: path("M5 3L15 3C16.6569 3 18 4.3431 18 6L18 7C19.6569 7 21 8.3431 21 10L21 18C21 19.6569 19.6569 21 18 21L6 21C4.3431 21 3 19.6569 3 18L3 5C3 3.8954 3.8954 3 5 3ZM3 5C3 6.1046 3.8954 7 5 7L18 7M21 12L18 12C16.8954 12 16 12.8954 16 14C16 15.1046 16.8954 16 18 16L21 16");
}

.zyz40f3pg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2L15 2C17.2091 2 19 3.7909 19 6L19 6.127C20.7661 6.583 22 8.176 22 10L22 18C22 20.2091 20.2091 22 18 22L6 22C3.7909 22 2 20.2091 2 18L2 5C2 3.3431 3.3431 2 5 2Z");
  stroke: none;
}

</style>
