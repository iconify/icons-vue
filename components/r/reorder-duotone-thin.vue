<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ci4oydb4u"/><path class="w69svbcwu"/><path class="am7eiccgy"/><path class="gms_xv68n"/><path class="pal6q2b_r"/><path class="lr_16ccln"/><path class="sxy07wbdf"/><path class="eu9kkgbdm"/><path class="x3jqftbaj"/><path class="r3faxubne"/><path class="weza57brb"/><path class="al6h6yb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reorder-duotone-thin" /></template>
<style>
.al6h6yb3y {
  d: path("m2 18 2 2 2 -2");
}

.am7eiccgy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ci4oydb4u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eu9kkgbdm {
  d: path("M9 12h12");
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

.lr_16ccln {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 18 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pal6q2b_r {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 6 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.sxy07wbdf {
  d: path("M9 7h12");
}

.w69svbcwu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.weza57brb {
  d: path("m2 6 2 -2 2 2");
}

.x3jqftbaj {
  d: path("M9 17h12");
}

</style>
