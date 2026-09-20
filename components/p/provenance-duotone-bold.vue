<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jz9jnbbik"/><path class="y36t9bcby"/><path class="ze6_11znx"/><path class="phefmrbhr"/><path class="t2b3_8bfb"/><path class="aeyekmbly"/><path class="axr3xwb0d"/><path class="yk3ngthye"/><path class="dx_oex_yx"/><path class="umr6jbb1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:provenance-duotone-bold" /></template>
<style>
.aeyekmbly {
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.axr3xwb0d {
  d: path("m7 17 4 -4");
}

.dx_oex_yx {
  d: path("m15 9 4 -4");
}

.jz9jnbbik {
  fill: currentColor;
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.phefmrbhr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 17 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t2b3_8bfb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 9 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.umr6jbb1c {
  d: path("M18 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.y36t9bcby {
  fill: currentColor;
  d: path("M11 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yk3ngthye {
  d: path("M11 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ze6_11znx {
  fill: currentColor;
  d: path("M18 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
