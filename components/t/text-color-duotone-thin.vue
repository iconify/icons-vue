<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uprf-9awp"/><path class="i1fmo_ukz"/><path class="e7x4xvbwr"/><path class="sqsxh9blm"/><path class="tklpoac2f"/><path class="ui32hib9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-color-duotone-thin" /></template>
<style>
.e7x4xvbwr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 20h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1fmo_ukz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 5v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sqsxh9blm {
  d: path("M5 5h14");
}

.tklpoac2f {
  d: path("M12 5v10");
}

.ui32hib9b {
  d: path("M5 20h14");
}

.uprf-9awp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 5h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
