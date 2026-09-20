<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pux-8e3tz"/><path class="sj5kv5bwz"/><path class="cacmi2bmi"/><path class="nxt-uwbql"/><path class="j8ahhogzn"/><path class="gxa8_gbhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-resource-subscribe-duotone-thin" /></template>
<style>
.cacmi2bmi {
  d: path("M13 3H9L6 6v15h12V8");
}

.gxa8_gbhz {
  d: path("M9 17a7 7 0 0 1 7 -7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8ahhogzn {
  d: path("M12 17a4 4 0 0 1 4 -4");
}

.nxt-uwbql {
  d: path("M15 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.pux-8e3tz {
  fill: currentColor;
  d: path("M13 3H9L6 6v15h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.sj5kv5bwz {
  fill: currentColor;
  d: path("M15 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
