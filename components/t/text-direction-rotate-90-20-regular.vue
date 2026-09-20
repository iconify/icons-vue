<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="yisrqulxo"/><path class="qx767_b4y"/><path class="db8ej_bjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-90-20-regular" /></template>
<style>
.db8ej_bjf {
  d: path("M13 10.5a.5.5 0 1 1 1 0v4.793l1.146-1.146a.5.5 0 0 1 .708.707l-2 2a.5.5 0 0 1-.708 0l-2-2a.5.5 0 0 1 .708-.707L13 15.293V10.5z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.qx767_b4y {
  d: path("M5 3.5a.5.5 0 0 1 1 0v11.793l1.146-1.146a.5.5 0 1 1 .708.707l-2 2a.498.498 0 0 1-.351.146h-.006a.498.498 0 0 1-.35-.146l-2-2a.5.5 0 1 1 .707-.707L5 15.293V3.5z");
  fill: currentColor;
}

.yisrqulxo {
  d: path("M17 6.5a.5.5 0 0 0-.324-.468l-8-3a.5.5 0 1 0-.351.936L11 4.972v3.057L8.325 9.032a.5.5 0 0 0 .35.936l8-3A.5.5 0 0 0 17 6.5zm-1.924 0L12 7.654V5.347L15.076 6.5z");
  fill: currentColor;
}

</style>
