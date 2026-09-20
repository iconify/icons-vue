<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="t8qt32blf"/><path class="eimg1ibhu"/><path class="qcb83wbuk"/><path class="chimp-scj"/><path class="k6nj2fbya"/><path class="d223d_x9q"/><path class="l517yxbln"/><path class="uxy9sxbfx"/><path class="z5zbrh5-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multi-cursor-duotone-thin" /></template>
<style>
.chimp-scj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 16v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ck7sgubpk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d223d_x9q {
  d: path("M3 12h6");
}

.eimg1ibhu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.l517yxbln {
  d: path("M12 9v6");
}

.qcb83wbuk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t8qt32blf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uxy9sxbfx {
  d: path("M3 19h10");
}

.z5zbrh5-r {
  d: path("M16 16v6");
}

</style>
