<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="osltrsbvo"/><path class="eimg1ibhu"/><path class="m89us6n4x"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="f26bn-hui"/><path class="l517yxbln"/><path class="dti01qb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scrape-interval-duotone-thin" /></template>
<style>
.dti01qb8s {
  d: path("M16 9v6");
}

.eimg1ibhu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f26bn-hui {
  d: path("M8 9v6");
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

.l517yxbln {
  d: path("M12 9v6");
}

.m89us6n4x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.osltrsbvo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
