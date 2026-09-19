<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zud_8ibhe"/><path class="xm_pooz_w"/><circle class="d1uffop4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oplayer" /></template>
<style>
.d1uffop4h {
  cx: 42.905px;
  cy: 19.927px;
  r: 2.243px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xm_pooz_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.7 24l-13-7.51v15.02z");
}

.zud_8ibhe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.905 34.248a21.5 21.5 0 1 1-.01-20.516");
}

</style>
