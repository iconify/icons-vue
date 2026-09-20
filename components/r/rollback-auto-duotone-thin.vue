<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vws5wpblq"/><path class="zvtk1r3pr"/><path class="eq1xvnr2k"/><path class="ri2m-q_tv"/><path class="wwogglmvt"/><path class="lpz1dcbuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rollback-auto-duotone-thin" /></template>
<style>
.eq1xvnr2k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.5 9.5 9 12l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpz1dcbuc {
  d: path("M11.5 9.5 9 12l2.5 2.5");
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.vws5wpblq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wwogglmvt {
  d: path("M9 12h8");
}

.zvtk1r3pr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
