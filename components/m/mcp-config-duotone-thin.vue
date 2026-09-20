<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="exn420ato"/><path class="ni20md-jo"/><path class="n8sqmebht"/><path class="l0zc9ibud"/><path class="q534om6ef"/><path class="c4khiwgvb"/><path class="tldtqlb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-config-duotone-thin" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.exn420ato {
  fill: currentColor;
  d: path("M13.5 3H17a3 3 0 0 1 3 3v12a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V6l3 -3h3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0zc9ibud {
  d: path("M8 10h8");
}

.n8sqmebht {
  d: path("M7 18h10");
}

.ni20md-jo {
  d: path("M13.5 3H17a3 3 0 0 1 3 3v12a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V6l3 -3h3.5");
}

.q534om6ef {
  d: path("M14 8v4");
}

.tldtqlb3m {
  d: path("M10 13v4");
}

</style>
