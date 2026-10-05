<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hqqnpbcmt"/><path class="c18elxbhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-nfc-two-tone" /></template>
<style>
.c18elxbhi {
  d: path("M5 4L9 4C10.6569 4 12 5.3431 12 7L12 17C12 18.6569 10.6569 20 9 20L5 20C3.3431 20 2 18.6569 2 17L2 7C2 5.3431 3.3431 4 5 4ZM6 8L8 8M17.4283 8.5C17.8069 9.6281 18 10.8101 18 12C18 13.1899 17.8069 14.3719 17.4283 15.5M21.3091 7.5C21.767 8.9561 22 10.4736 22 12C22 13.5264 21.767 15.0439 21.3091 16.5");
}

.hqqnpbcmt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 3C11.2092 3 13 4.79082 13 7V17C13 19.2092 11.2092 21 9 21H5C2.79082 21 1 19.2092 1 17V7C1 4.79082 2.79082 3 5 3H9Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
