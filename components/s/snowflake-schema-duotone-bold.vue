<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jdwartbwj"/><path class="wt1fwbbaa"/><path class="oong2tffv"/><path class="meb7wcbot"/><path class="xr_3yjbwe"/><path class="jga19gb8p"/><path class="eev_c9mlp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:snowflake-schema-duotone-bold" /></template>
<style>
.eev_c9mlp {
  d: path("m7 20 5 -5 5 5");
}

.jdwartbwj {
  fill: currentColor;
  d: path("M8 12.5a2.5 2.5 0 0 1 2.5 -2.5h3a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-3A2.5 2.5 0 0 1 8 12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jga19gb8p {
  d: path("M17 5v3");
}

.meb7wcbot {
  d: path("M7 5h10");
}

.oong2tffv {
  d: path("M12 5v5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wt1fwbbaa {
  d: path("M8 12.5a2.5 2.5 0 0 1 2.5 -2.5h3a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-3A2.5 2.5 0 0 1 8 12.5");
}

.xr_3yjbwe {
  d: path("M7 5v3");
}

</style>
