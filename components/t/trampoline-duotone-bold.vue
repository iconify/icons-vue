<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jzeve79sx"/><path class="qewuh9pgi"/><path class="izztv2bmh"/><path class="llep1obfh"/><path class="yhxg0gb1u"/><path class="ifnz35boy"/><path class="wp14ejvwu"/><path class="ymw3aibdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trampoline-duotone-bold" /></template>
<style>
.ifnz35boy {
  d: path("M5 12v8");
}

.izztv2bmh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jzeve79sx {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.llep1obfh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qewuh9pgi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11c4 3 14 3 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wp14ejvwu {
  d: path("M19 12v8");
}

.yhxg0gb1u {
  d: path("M3 11c4 3 14 3 18 0");
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
