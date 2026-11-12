<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsrhfac5n"/><path class="cyf8bssrf"/><path class="k342tsbcj"/><path class="bqq4qs3tr"/><path class="zn2hzfs5j"/><path class="ki00rvofo"/><path class="v4sczhx0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-large-off-line-duotone" /></template>
<style>
.bqq4qs3tr {
  d: path("M3 11V13C3 15.231 3.812 17.272 5.156 18.844");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.cyf8bssrf {
  d: path("M7.287 16.713C6.481 15.692 6 14.402 6 13V8C6 4.6863 8.6863 2 12 2C14.708 2 16.996 3.793 17.742 6.258");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k342tsbcj {
  d: path("M18.001 9.45605V13.0001C18.001 16.3138 15.3147 19.0001 12.001 19.0001C10.961 19.0001 9.98097 18.7361 9.16797 18.2891");
}

.ki00rvofo {
  d: path("M10 6.5C10 6.5 10.4727 6 12 6C13.5273 6 14 6.5 14 6.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

.v4sczhx0t {
  d: path("M10 9.5C10 9.5 10.4727 9 12 9C13.5273 9 14 9.5 14 9.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zn2hzfs5j {
  d: path("M6.98047 20.47C8.41047 21.43 10.1405 22 12.0005 22C16.9715 22 21.0005 17.971 21.0005 13V11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
