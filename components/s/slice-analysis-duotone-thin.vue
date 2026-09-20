<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="efnmt0b_s"/><path class="ey8kebcwj"/><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="xvqqitb7t"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="oe-98mb0w"/><path class="c8tpvpbrt"/><path class="igggo2bgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:slice-analysis-duotone-thin" /></template>
<style>
.c8tpvpbrt {
  d: path("M7 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.efnmt0b_s {
  fill: currentColor;
  d: path("M7 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ey8kebcwj {
  fill: currentColor;
  d: path("M15 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
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

.igggo2bgi {
  d: path("M15 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.oe-98mb0w {
  d: path("M12 6v12");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.xvqqitb7t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
