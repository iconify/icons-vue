<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_bfpevyh"/><path class="rencte-ct"/><path class="i8wcjxb1o"/><path class="o5g--7b4b"/><path class="a6ddgjbst"/><path class="zjs6ad-6z"/><path class="tdux9oy4s"/><path class="iwpbli9gm"/><path class="h57xi_b4m"/><path class="et81l2oxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multi-hop-duotone-thin" /></template>
<style>
.a6ddgjbst {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 14a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.et81l2oxt {
  d: path("M12 14a4 4 0 0 1 8 0");
}

.h57xi_b4m {
  d: path("M4 14a4 4 0 0 1 8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_bfpevyh {
  fill: currentColor;
  d: path("M2 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.i8wcjxb1o {
  fill: currentColor;
  d: path("M18 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iwpbli9gm {
  d: path("M18 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.o5g--7b4b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 14a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rencte-ct {
  fill: currentColor;
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tdux9oy4s {
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zjs6ad-6z {
  d: path("M2 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
