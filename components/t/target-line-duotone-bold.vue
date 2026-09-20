<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mpmgljbgd"/><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="okds9dbso"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e_6o-gbms"/><path class="blo0wbrjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:target-line-duotone-bold" /></template>
<style>
.blo0wbrjk {
  d: path("M11 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e_6o-gbms {
  d: path("M6 10h13");
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.okds9dbso {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
