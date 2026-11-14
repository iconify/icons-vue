<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lxe6a3hsw"/><path class="pbeiyabda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sperm-test" /></template>
<style>
.lxe6a3hsw {
  d: path("M11.5 7a3.5 2.5 0 1 0 7 0a3.5 2.5 0 1 0-7 0Zm1 2.5C10 12 12 14 9.5 16S5 17.5 3 21m13.25-6.75v5.25c0 2.25 3.5 2.25 3.5 0v-5.25m-4.5 0h5.5");
}

.pbeiyabda {
  fill: currentColor;
  d: path("M16.25 17.5h3.5v2c0 2.25-3.5 2.25-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
