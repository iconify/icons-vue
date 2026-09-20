<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sp9didc2k"/><path class="xz0dmcbcb"/><path class="va2q3vb-t"/><path class="s994z3b0d"/><path class="ubojtpbkq"/><path class="vhf3_kexp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pin-duotone-bold" /></template>
<style>
.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s994z3b0d {
  d: path("M6 5h12");
}

.sp9didc2k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ubojtpbkq {
  d: path("M9 5v8l3 3 3 -3V5");
}

.va2q3vb-t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 16v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vhf3_kexp {
  d: path("M12 16v5");
}

.xz0dmcbcb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 5v8l3 3 3 -3V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
