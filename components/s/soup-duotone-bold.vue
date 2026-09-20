<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vow7fbbnh"/><path class="xi253xtcz"/><path class="comy-yirf"/><path class="akhrngbmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:soup-duotone-bold" /></template>
<style>
.akhrngbmf {
  d: path("M15 10c2 -2 0 -4 2 -6");
}

.comy-yirf {
  d: path("M9 10c2 -2 0 -4 2 -6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vow7fbbnh {
  fill: currentColor;
  d: path("M4 12h16c0 5 -4 9 -8 9s-8 -4 -8 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xi253xtcz {
  d: path("M4 12h16c0 5 -4 9 -8 9s-8 -4 -8 -9");
}

</style>
