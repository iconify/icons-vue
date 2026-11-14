<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vg8s5abzj"/><path class="p4_kdlbtd"/><path class="gvr4sabwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:multisig" /></template>
<style>
.gvr4sabwn {
  d: path("M8 12.75V21h2.75M16 12.75V21h2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4_kdlbtd {
  d: path("M5.5 10.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m8 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.vg8s5abzj {
  d: path("M8 7.75a4 4 0 0 1 8 0");
}

</style>
