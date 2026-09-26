<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wo3he8bkq"/><path class="usm8m5btb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:whole-word-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.usm8m5btb {
  d: path("M10 11C10 12.6569 8.6569 14 7 14C5.3431 14 4 12.6569 4 11C4 9.3431 5.3431 8 7 8C8.6569 8 10 9.3431 10 11ZM10 8L10 14M14 4L14 14M20 11C20 12.6569 18.6569 14 17 14C15.3431 14 14 12.6569 14 11C14 9.3431 15.3431 8 17 8C18.6569 8 20 9.3431 20 11Z");
}

.wo3he8bkq {
  stroke-opacity: 0.4;
  d: path("M2 17L2 18C2 19.1046 2.8954 20 4 20L20 20C21.1046 20 22 19.1046 22 18L22 17");
}

</style>
