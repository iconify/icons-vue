<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ga65sabzo"/><path class="e95s_yp3q"/><path class="e4go3nb7x"/><path class="a6e_o0bju"/><path class="dvfmj91gv"/><path class="kp1e7wcsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:property-invest-duotone-bold" /></template>
<style>
.a6e_o0bju {
  d: path("m3 11 9 -9 9 9");
}

.dvfmj91gv {
  d: path("M6 11v10h12V11");
}

.e4go3nb7x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 19 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e95s_yp3q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 11v10h12V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ga65sabzo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 11 9 -9 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kp1e7wcsa {
  d: path("m9 19 2 -2 2 2 2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
