<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lqpnckb6o"/><path class="l16e3bc6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:task-success" /></template>
<style>
.l16e3bc6f {
  d: path("m8 12.5l3 3l5-6");
}

.lqpnckb6o {
  d: path("m12 2.5l8.227 4.75v9.5L12 21.5l-8.227-4.75v-9.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
