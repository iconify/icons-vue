<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t87sbq9qb"/><path class="y8zdbi5ol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:subscript-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t87sbq9qb {
  stroke-opacity: 0.4;
  d: path("M2 4L12 16M12 4L2 16");
}

.y8zdbi5ol {
  d: path("M16.75 15.1L19 13V20M16 20H22");
}

</style>
