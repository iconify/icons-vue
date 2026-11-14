<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="afjmqabbu"/><path class="u9_i14azq"/><path class="ro5dg0wjp"/><path class="irnup5byk"/><path class="qc1rb6b7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:yen-linear" /></template>
<style>
.afjmqabbu {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irnup5byk {
  d: path("M9.25 12H14.75");
}

.qc1rb6b7c {
  d: path("M9.25 14.5H14.75");
}

.ro5dg0wjp {
  d: path("M12 12V17");
}

.u9_i14azq {
  d: path("M8.5 7L12 12L15.5 7");
}

</style>
