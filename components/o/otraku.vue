<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e4c0zmatc"/><path class="xqzyaac_v"/><path class="q2xn2jqpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:otraku" /></template>
<style>
.e4c0zmatc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.753 40.676c.62-10.293 1.17-16.607.851-28.441M24 8.48A140 140 0 0 1 4.5 7.323");
}

.q2xn2jqpt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.526v3.778H10.058m24.19 24.372c-.62-10.293-1.17-16.607-.852-28.441M24 8.48a140 140 0 0 0 19.5-1.156M24 12.526zm0 3.778h13.942");
}

.xqzyaac_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.73 7.716l-.038 3.792A112 112 0 0 0 24 12.526a112 112 0 0 0 16.308-1.018l.012-3.797");
}

</style>
