<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ot9ye4b0y"/><path class="wics1lbun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-ringing-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ot9ye4b0y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 3C16.2092 3 18 4.79082 18 7V17C18 19.2092 16.2092 21 14 21H10C7.79082 21 6 19.2092 6 17V7C6 4.79082 7.79082 3 10 3H14Z");
  stroke: none;
}

.wics1lbun {
  d: path("M10 4L14 4C15.6569 4 17 5.3431 17 7L17 17C17 18.6569 15.6569 20 14 20L10 20C8.3431 20 7 18.6569 7 17L7 7C7 5.3431 8.3431 4 10 4ZM11 8L13 8M21.3675 8.5C21.7858 9.6195 22 10.8049 22 12C22 13.1951 21.7858 14.3805 21.3675 15.5M2.6325 15.5C2.2142 14.3805 2 13.1951 2 12C2 10.8049 2.2142 9.6195 2.6325 8.5");
}

</style>
