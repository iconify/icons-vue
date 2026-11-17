<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w3y6jop0a"/><path class="ifgz10bgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:route-2-duotone" /></template>
<style>
.ifgz10bgv {
  d: path("M15 5H10.5C8.567 5 7 6.567 7 8.5C7 10.433 8.567 12 10.5 12H14.5C16.433 12 18 13.567 18 15.5C18 17.433 16.433 19 14.5 19H9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w3y6jop0a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 15C8.209 15 10 16.791 10 19C10 21.209 8.209 23 6 23C3.791 23 2 21.209 2 19C2 16.791 3.791 15 6 15ZM18 1C20.209 1 22 2.791 22 5C22 7.209 20.209 9 18 9C15.791 9 14 7.209 14 5C14 2.791 15.791 1 18 1Z");
  stroke: none;
}

</style>
