<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pcyyhibmg"/><path class="c3342844d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:saveto" /></template>
<style>
.c3342844d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.92 5.5h22.16v10.25H12.92zm0 21.25h22.16V42.5H12.92zm18.72-14.51V9.01M17.79 31.93h12.42m-12.42 5.39h12.42");
}

.pcyyhibmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 10.18L10 5.5h30.5a2 2 0 0 1 2 2v33a2 2 0 0 1-2 2h-33a2 2 0 0 1-2-2Z");
}

</style>
