<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k03z74m2p"/><path class="qcdrd6x6f"/><path class="s3jkkrb6o"/><path class="uhjffo8gx"/><path class="uf-j07bpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sightseeing-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k03z74m2p {
  fill: currentColor;
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qcdrd6x6f {
  fill: currentColor;
  d: path("M8 13.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s3jkkrb6o {
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.uf-j07bpp {
  d: path("m8 7 2.5 -2.5h3L16 7");
}

.uhjffo8gx {
  d: path("M8 13.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
