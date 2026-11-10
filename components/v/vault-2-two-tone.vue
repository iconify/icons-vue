<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ddzk63b3h"/><path class="b63c889xu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vault-2-two-tone" /></template>
<style>
.b63c889xu {
  d: path("M14.5 9.5L17 7M7 17L9.5 14.5M17 17L14.5 14.5M9.5 9.5L7 7M6 3H18C19.6569 3 21 4.34 21 6V18C21 19.66 19.6569 21 18 21H6C4.3431 21 3 19.66 3 18V6C3 4.34 4.3431 3 6 3ZM12 15C10.3431 15 9 13.66 9 12C9 10.34 10.3431 9 12 9C13.6569 9 15 10.34 15 12C15 13.66 13.6569 15 12 15Z");
}

.ddzk63b3h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 2C20.2092 2 22 3.79 22 6V18C22 20.21 20.2092 22 18 22H6C3.7908 22 2 20.21 2 18V6C2 3.79 3.7908 2 6 2H18Z");
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
