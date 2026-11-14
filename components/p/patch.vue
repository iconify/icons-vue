<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lojg4k8pq"/><path class="sn03i2kpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:patch" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lojg4k8pq {
  d: path("m5.636 14.121l8.485-8.485a3 3 0 0 1 4.243 0a3 3 0 0 1 0 4.243l-8.485 8.485a3 3 0 0 1-4.243 0a3 3 0 0 1 0-4.243");
}

.sn03i2kpy {
  d: path("m8.818 10.939l2.121-2.121a1.5 1.5 0 0 1 2.122 0l2.121 2.121a1.5 1.5 0 0 1 0 2.122l-2.121 2.121a1.5 1.5 0 0 1-2.122 0l-2.121-2.121a1.5 1.5 0 0 1 0-2.122M11 11h.01M13 13h.01");
}

</style>
