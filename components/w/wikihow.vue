<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v50hvbb1q"/><path class="uwgtzqz-f"/><circle class="q78gucc-d"/><path class="qjp98gtcs"/><circle class="qrbc391xx"/><path class="zgemzl7fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wikihow" /></template>
<style>
.q78gucc-d {
  cx: 23px;
  cy: 12.9px;
  r: 0.75px;
  fill: currentColor;
}

.qjp98gtcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23 15.9v6.6");
}

.qrbc391xx {
  cx: 34.9px;
  cy: 12.9px;
  r: 0.75px;
  fill: currentColor;
}

.uwgtzqz-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.8 15.9l-2 6.6l-2.1-6.6l-2 6.6l-2.1-6.6M23.8 36zc-1.4 0-2.5-1.1-2.5-2.5v-1.6c0-1.4 1.1-2.5 2.5-2.5s2.5 1.1 2.5 2.5v1.6c0 1.4-1.1 2.5-2.5 2.5m3-23.4v9.9m0-2.1l4.5-4.5m-3 3.1l3.5 3.5");
}

.v50hvbb1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4M12 26.1V36m6.5-9.9V36M12 31h6.5");
}

.zgemzl7fh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.9 15.9v6.6m1.5 6.9l-2 6.6l-2.1-6.6l-2 6.6l-2-6.6");
}

</style>
