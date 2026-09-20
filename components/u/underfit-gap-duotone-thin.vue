<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5rxwxb6q"/><path class="p_44--b8v"/><path class="sb_u66zcg"/><path class="qe97cg-lx"/><path class="gnfxbib2f"/><path class="nyl8f3o_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:underfit-gap-duotone-thin" /></template>
<style>
.e5rxwxb6q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gnfxbib2f {
  d: path("M6 8h13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nyl8f3o_r {
  d: path("M6 13h13");
}

.p_44--b8v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

.sb_u66zcg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 13h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
