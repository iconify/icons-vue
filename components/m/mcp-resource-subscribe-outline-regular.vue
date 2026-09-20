<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cacmi2bmi"/><path class="nxt-uwbql"/><path class="j8ahhogzn"/><path class="gxa8_gbhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-resource-subscribe-outline-regular" /></template>
<style>
.cacmi2bmi {
  d: path("M13 3H9L6 6v15h12V8");
}

.gxa8_gbhz {
  d: path("M9 17a7 7 0 0 1 7 -7");
}

.j8ahhogzn {
  d: path("M12 17a4 4 0 0 1 4 -4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nxt-uwbql {
  d: path("M15 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
