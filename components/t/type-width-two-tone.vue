<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hm4qk0qph"/><path class="bykupebux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type-width-two-tone" /></template>
<style>
.bykupebux {
  d: path("M20 19H4M17 16L20 19L17 22M7 16L4 19L7 22");
}

.hm4qk0qph {
  stroke-opacity: 0.4;
  d: path("M4 5V4C4 2.8954 4.8954 2 6 2H18C19.1046 2 20 2.8954 20 4V5M12 2V12M8.5 12H15.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
