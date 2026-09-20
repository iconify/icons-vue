<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jrq8s6__w"/><path class="yipk7w_dp"/><path class="fh4vasbnq"/><path class="us2evabuy"/><path class="wzsyjh0wp"/><path class="prbp3oa5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pot-duotone-bold" /></template>
<style>
.fh4vasbnq {
  d: path("M8 12a4 4 0 0 1 8 0");
}

.jrq8s6__w {
  fill: currentColor;
  d: path("M5 12v7h14v-7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.prbp3oa5j {
  d: path("M19 15h3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.us2evabuy {
  d: path("M12 5.5V8");
}

.wzsyjh0wp {
  d: path("M2 15h3");
}

.yipk7w_dp {
  d: path("M5 12v7h14v-7Z");
}

</style>
