<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wc84ktb0x"/><path class="o_r3tojiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:repeat-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_r3tojiu {
  d: path("M21 12L21 15C21 16.6569 19.6569 18 18 18L3 18M6 21L3 18L6 15");
}

.wc84ktb0x {
  stroke-opacity: 0.4;
  d: path("M3 12L3 9C3 7.3432 4.3431 6 6 6L21 6M18 3L21 6L18 9");
}

</style>
