<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r6xi4ylro"/><path class="lw912obya"/><path class="vm55gtbfg"/><path class="xslwtfbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wheelbarrow-outline-regular" /></template>
<style>
.lw912obya {
  d: path("m18 9 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r6xi4ylro {
  d: path("M4 8h14l-3 3H7Z");
}

.vm55gtbfg {
  d: path("M4 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.xslwtfbwz {
  d: path("M15 11v6");
}

</style>
