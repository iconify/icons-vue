<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eknhjzvmo"/><path class="kb4ca79fq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:z-order-duotone-regular" /></template>
<style>
.eknhjzvmo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5h16L6 19h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kb4ca79fq {
  d: path("M4 5h16L6 19h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
