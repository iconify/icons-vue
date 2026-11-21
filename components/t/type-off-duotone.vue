<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qoo5bm6cn"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qoo5bm6cn {
  stroke-opacity: 0.4;
  d: path("M4 6V5C4 4.7065 4.0632 4.4278 4.1767 4.1767M8.6569 3H18C19.1046 3 20 3.8954 20 5V6M12 3V6.3431M12 21V12M8.6569 21H15.3431");
}

</style>
