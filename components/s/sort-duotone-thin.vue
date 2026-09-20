<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="s2ztwmbwx"/><path class="cvqe-8bsy"/><path class="xgrfb-bqu"/><path class="bj2hlhbfp"/><path class="d_scobift"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sort-duotone-thin" /></template>
<style>
.bj2hlhbfp {
  d: path("M3 12h12");
}

.cvqe-8bsy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d_scobift {
  d: path("M3 18h6");
}

.earhjk-cy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s2ztwmbwx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
