<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q8k8d3bmd"/><path class="m0jf1ib7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sign-lease" /></template>
<style>
.m0jf1ib7i {
  d: path("M8.5 12.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6 7.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3-1.25l3.75-3.75m-1.5 1.5l1.5 1.5");
}

.q8k8d3bmd {
  d: path("M11.98 18.261L10 21.5l-5.5-9l2-6.5h7l2 6.5l-2.53 4.139M6.5 6V3h7v3M10 21.5V14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
