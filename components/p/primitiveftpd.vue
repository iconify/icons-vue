<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lpkd84gme"/><path class="n5l5w7gfh"/><path class="ruwbvtb0q"/><rect class="yzm59coui"/><path class="p__7zry0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:primitiveftpd" /></template>
<style>
.lpkd84gme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.72 31.65c1.93 3.34 2 6 0 9.31m-2.12-7.71a5.56 5.56 0 0 1 0 6.1m-2.1-4.54a2.25 2.25 0 0 1 0 3l-2-1.53Z");
}

.n5l5w7gfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.38 28.37a7.95 7.95 0 1 0 7.94 7.94a7.93 7.93 0 0 0-7.93-7.93Z");
}

.p__7zry0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.51 17.78v9.32m-1.62-6.2h3.25m-7.93 6.2v-6.99m2.33-2.33za2.33 2.33 0 0 0-2.33 2.33m0 .79h2.33m-3.14 0h.81");
}

.ruwbvtb0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 29V15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h22.56m-4.56-39l11 11M22.48 30.22V20.9");
}

.yzm59coui {
  width: 4.66px;
  height: 6.19px;
  x: 22.48px;
  y: 20.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.33px;
}

</style>
