<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lqpnckb6o"/><path class="rbymc7b-p"/><path class="kjwvv4q0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:task-retry" /></template>
<style>
.kjwvv4q0k {
  d: path("m9.25 13.25l-1.5-2l-1.5 2");
}

.lqpnckb6o {
  d: path("m12 2.5l8.227 4.75v9.5L12 21.5l-8.227-4.75v-9.5Z");
}

.rbymc7b-p {
  d: path("M8.995 8.995A4.25 4.25 0 1 1 7.75 12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
