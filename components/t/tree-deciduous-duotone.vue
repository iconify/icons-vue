<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dvzumcbbe"/><path class="xh-9600kv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tree-deciduous-duotone" /></template>
<style>
.dvzumcbbe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.8746 5.5015C7.6987 3.39 9.7334 2 12 2C14.2666 2 16.3013 3.39 17.1254 5.5015C19.8375 5.5691 22.001 7.7872 22.001 10.5002C22.001 12.3223 21.0098 14.0002 19.4138 14.8796C18.9948 16.9847 17.1472 18.5008 15.0007 18.5008C13.8935 18.5008 12.8251 18.0925 12 17.3541C11.1749 18.0925 10.1065 18.5008 8.9993 18.5008C6.8528 18.5008 5.0052 16.9847 4.5861 14.8795C2.9902 14.0001 1.999 12.3223 1.999 10.5002C1.999 7.7872 4.1625 5.5691 6.8746 5.5015Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xh-9600kv {
  d: path("M12 21L12 11.5M10.5 10L12 11.5L13.5 10");
}

</style>
