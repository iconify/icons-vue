<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="qnvjj7b8l"/><path class="y0-7dcbun"/><path class="nk4ly60-c"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="pr2xdw8hh"/><path class="a67_cn3fi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:next-milestone-duotone-regular" /></template>
<style>
.a67_cn3fi {
  d: path("M13.5 7.5 16 10l-2.5 2.5");
}

.crv4i00bu {
  d: path("M4 3v18");
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.nk4ly60-c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 7.5 16 10l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pr2xdw8hh {
  d: path("M10.5 7.5 13 10l-2.5 2.5");
}

.qlvopac9f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qnvjj7b8l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y0-7dcbun {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 7.5 13 10l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
