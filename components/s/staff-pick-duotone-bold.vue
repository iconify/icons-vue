<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hmkpulkfg"/><path class="fkim6rbtt"/><path class="adxensbci"/><path class="nmwlt6bbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:staff-pick-duotone-bold" /></template>
<style>
.adxensbci {
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
}

.fkim6rbtt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 8.5 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hmkpulkfg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nmwlt6bbh {
  d: path("m9 8.5 2 2 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
