<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bmgfadc9p"/><path class="l0imm6dml"/><path class="mg809lb3t"/><path class="pg64rfbtc"/><path class="y8a66ib3e"/><path class="p4weyfsrl"/><path class="l9rn44bjs"/><path class="w0e70wbbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sandbag-duotone-thin" /></template>
<style>
.bmgfadc9p {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0imm6dml {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l9rn44bjs {
  d: path("m10.5 8 3 3");
}

.mg809lb3t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10.5 8 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p4weyfsrl {
  d: path("M16 13v6");
}

.pg64rfbtc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21.5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w0e70wbbt {
  d: path("M3 21.5h18");
}

.y8a66ib3e {
  d: path("M8 4v15");
}

</style>
