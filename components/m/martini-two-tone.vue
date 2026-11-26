<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="az--m0bwu"/><path class="ce9btvbgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:martini-two-tone" /></template>
<style>
.az--m0bwu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2L20.998 2C21.887 2 22.5623 2.5504 22.8457 3.2346C23.1291 3.9189 23.0408 4.7856 22.4123 5.4142L13.7678 14.0586C12.7915 15.0349 11.2085 15.0349 10.2322 14.0586L1.5878 5.4142C0.9592 4.7856 0.8709 3.9189 1.1543 3.2346C1.4377 2.5504 2.113 2 3.002 2Z");
  stroke: none;
}

.ce9btvbgb {
  d: path("M3.002 3H20.998C21.8889 3 22.335 4.0771 21.7051 4.7071L13.0607 13.3515C12.4749 13.9373 11.5251 13.9373 10.9393 13.3515L2.2949 4.7071C1.665 4.0771 2.1111 3 3.002 3ZM4.5878 7H19.4122M12 13.7909V21M6 21H18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
