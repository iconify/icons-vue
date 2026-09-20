<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mpmgljbgd"/><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="wmj0hybky"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e_6o-gbms"/><path class="blo0wbrjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:target-line-duotone-thin" /></template>
<style>
.blo0wbrjk {
  d: path("M11 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.e_6o-gbms {
  d: path("M6 10h13");
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mpmgljbgd {
  fill: currentColor;
  d: path("M11 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.wmj0hybky {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 10h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
