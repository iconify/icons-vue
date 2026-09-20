<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="efnmt0b_s"/><path class="ey8kebcwj"/><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="tyvw42b6f"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="oe-98mb0w"/><path class="c8tpvpbrt"/><path class="igggo2bgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:slice-analysis-duotone-bold" /></template>
<style>
.c8tpvpbrt {
  d: path("M7 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.igggo2bgi {
  d: path("M15 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tyvw42b6f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
