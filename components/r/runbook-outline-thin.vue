<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abnm6smsv"/><path class="c4o3x9bhp"/><path class="t7gelxb9v"/><path class="teamv5bhf"/><path class="cn1mb64lb"/><path class="tcg96lbqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:runbook-outline-thin" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.c4o3x9bhp {
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.cn1mb64lb {
  d: path("M11 13h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t7gelxb9v {
  d: path("M11 9h4");
}

.tcg96lbqc {
  d: path("m10 16 2 2 -2 2");
}

.teamv5bhf {
  d: path("M8 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
