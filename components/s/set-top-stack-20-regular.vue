<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="f_ivq2bpu"/><path class="cpuewv22t"/><path class="gecl-wbkh"/><path class="gf522acxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:set-top-stack-20-regular" /></template>
<style>
.cpuewv22t {
  d: path("M2 5a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5zm2-1a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1H4z");
  fill: currentColor;
}

.f_ivq2bpu {
  d: path("M8 4.75a.5.5 0 0 1 .443.268l.878 1.68l1.738.208a.5.5 0 0 1 .253.887l-1.254 1l.429 1.844a.5.5 0 0 1-.744.542L8 10.137l-1.743 1.042a.5.5 0 0 1-.744-.542l.429-1.845l-1.254-.999a.5.5 0 0 1 .253-.887l1.738-.208l.878-1.68A.5.5 0 0 1 8 4.75zm0 1.58l-.557 1.065a.5.5 0 0 1-.384.265l-.812.097l.565.45a.5.5 0 0 1 .175.504l-.234 1.006l.99-.592a.5.5 0 0 1 .514 0l.99.592l-.234-1.006a.5.5 0 0 1 .175-.504l.565-.45l-.812-.097a.5.5 0 0 1-.384-.265L8 6.329z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.gecl-wbkh {
  d: path("M6 15a2 2 0 0 1-1.732-1H12a3 3 0 0 0 3-3V5.268A2 2 0 0 1 16 7v4a4 4 0 0 1-4 4H6z");
  fill: currentColor;
}

.gf522acxc {
  d: path("M8 17a2 2 0 0 1-1.732-1H12a5 5 0 0 0 5-5V7.268A2 2 0 0 1 18 9v2a6 6 0 0 1-6 6H8z");
  fill: currentColor;
}

</style>
