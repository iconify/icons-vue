<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="igu3pvbml"/><path class="nwcqa3bxq"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="wdvszqb6r"/><path class="l0kkv4bte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:metric-cardinality-duotone-thin" /></template>
<style>
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

.igu3pvbml {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 5v12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l0kkv4bte {
  d: path("M7 17 17 7");
}

.nwcqa3bxq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 17 17 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.wdvszqb6r {
  d: path("M7 5v12h12");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
