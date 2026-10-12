<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xj1ywy_um"/><path class="ks_yxcs9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:open-house" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ks_yxcs9s {
  d: path("M9.5 21.25v-7h5.75v7m-6.22-7.18l-3.06-1.14q-.47-.18-.47.32v7.5q0 .5.5.5h3q.5 0 .5-.5v-6q0-.5-.47-.68");
}

.xj1ywy_um {
  d: path("M2.75 20.25v-9.1q0-1 .78-1.62l7.69-6.16q.78-.62 1.56 0l7.69 6.16q.78.62.78 1.62v9.1q0 1-1 1H3.75q-1 0-1-1");
}

</style>
