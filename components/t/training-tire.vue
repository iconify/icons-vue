<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f4tns0jdm"/><path class="kr4fvryln"/><path class="f6gjahqkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:training-tire" /></template>
<style>
.f4tns0jdm {
  d: path("M3 9.5a9 4.5 0 1 0 18 0a9 4.5 0 1 0-18 0Z");
}

.f6gjahqkn {
  d: path("M7.5 9.5a4.5 2 0 1 0 9 0a4.5 2 0 1 0-9 0Z");
}

.kr4fvryln {
  d: path("M3 9.5V14c0 2.5 4 4.5 9 4.5s9-2 9-4.5V9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
