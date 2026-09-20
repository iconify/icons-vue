<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="tqkj7rb5l"/><path class="bvjkfclbh"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="bw_to0b8d"/><path class="him6j9cua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:variance-duotone-bold" /></template>
<style>
.bvjkfclbh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 17 19 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bw_to0b8d {
  d: path("M7 12h12");
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.him6j9cua {
  d: path("M7 17 19 5");
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.tqkj7rb5l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
