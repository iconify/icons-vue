<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="hm_ld8t4k"/><path class="vkxl0abiv"/><path class="jt3dxp5dx"/><path class="jh6waltkl"/><path class="k6nj2fbya"/><path class="kif6g-eik"/><path class="enh0e8a0v"/><path class="hczrfxb9f"/><path class="qtxvlht3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:towel-rail-duotone-thin" /></template>
<style>
.ck7sgubpk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.enh0e8a0v {
  d: path("M21 5v3");
}

.hczrfxb9f {
  d: path("M8 5v15h8V5");
}

.hm_ld8t4k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jh6waltkl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jt3dxp5dx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 5v15h8V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.kif6g-eik {
  d: path("M3 5v3");
}

.qtxvlht3c {
  d: path("M8 17h8");
}

.vkxl0abiv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
