<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p8jvazqdv"/><path class="o4zw09imi"/><path class="r6xi4ylro"/><path class="lw912obya"/><path class="vm55gtbfg"/><path class="xslwtfbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wheelbarrow-duotone-bold" /></template>
<style>
.lw912obya {
  d: path("m18 9 3 3");
}

.o4zw09imi {
  fill: currentColor;
  d: path("M4 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.p8jvazqdv {
  fill: currentColor;
  d: path("M4 8h14l-3 3H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r6xi4ylro {
  d: path("M4 8h14l-3 3H7Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vm55gtbfg {
  d: path("M4 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.xslwtfbwz {
  d: path("M15 11v6");
}

</style>
