<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s89mo4b-k"/><path class="g6wquxbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zmenteto" /></template>
<style>
.g6wquxbpv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.969 24.158a9.112 9.112 0 1 1-18.224 0m18.224-.507h-2.531l2.53-4.556l2.532 4.556z");
}

.s89mo4b-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.612 14.73a9.112 9.112 0 1 0 0 18.224a9.112 9.112 0 0 0 0-18.223");
}

</style>
