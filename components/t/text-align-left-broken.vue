<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y8rchkbuh"/><path class="jgeg8bc0n"/><path class="k3es_jbnn"/><path class="vnh-5-_9e"/><path class="dnytl_40k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-align-left-broken" /></template>
<style>
.dnytl_40k {
  d: path("M5 18H14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jgeg8bc0n {
  d: path("M5 10H14");
}

.k3es_jbnn {
  d: path("M5 14H9.6");
}

.vnh-5-_9e {
  d: path("M13 14H19");
}

.y8rchkbuh {
  d: path("M5 6H19");
}

</style>
