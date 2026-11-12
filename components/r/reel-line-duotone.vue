<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="zc6fw0k_a"/><path class="qw6i-_b4t"/><path class="eijguwp1k"/><path class="na-h04rle"/><path class="f_wmpvm9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reel-line-duotone" /></template>
<style>
.eijguwp1k {
  d: path("M13.5 16.5C13.5 17.3284 12.8284 18 12 18C11.1716 18 10.5 17.3284 10.5 16.5C10.5 15.6716 11.1716 15 12 15C12.8284 15 13.5 15.6716 13.5 16.5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.f_wmpvm9m {
  d: path("M16.5 10.5C17.3284 10.5 18 11.1716 18 12C18 12.8284 17.3284 13.5 16.5 13.5C15.6716 13.5 15 12.8284 15 12C15 11.1716 15.6716 10.5 16.5 10.5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.na-h04rle {
  d: path("M7.5 10.5C8.32843 10.5 9 11.1716 9 12C9 12.8284 8.32843 13.5 7.5 13.5C6.67157 13.5 6 12.8284 6 12C6 11.1716 6.67157 10.5 7.5 10.5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qw6i-_b4t {
  d: path("M13.5 7.5C13.5 8.32843 12.8284 9 12 9C11.1716 9 10.5 8.32843 10.5 7.5C10.5 6.67157 11.1716 6 12 6C12.8284 6 13.5 6.67157 13.5 7.5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.shu3xdl9q {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

.zc6fw0k_a {
  d: path("M12 22L22 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
