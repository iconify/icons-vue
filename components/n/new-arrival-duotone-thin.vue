<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jkh2r59sx"/><path class="qrhqs_vfa"/><path class="ep4fagbhx"/><path class="gvexosb3b"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="t0w54r8ah"/><path class="ul0m4fbfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:new-arrival-duotone-thin" /></template>
<style>
.ep4fagbhx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 14 2.5 -2.5 2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gvexosb3b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 17.5h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkh2r59sx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qrhqs_vfa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t0w54r8ah {
  d: path("m9.5 14 2.5 -2.5 2.5 2.5");
}

.tp7101bon {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

.ul0m4fbfe {
  d: path("M9 17.5h6");
}

.yb0d-pkkp {
  d: path("M4 8v14h16V8");
}

</style>
