<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mbmrpw-rs"/><path class="v79iaqbup"/><path class="hbz-npylq"/><path class="j5qohtzrk"/><path class="ae-e09b3w"/><path class="f-g2d4bkj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-gust-duotone-bold" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.f-g2d4bkj {
  d: path("M8 17h10");
}

.hbz-npylq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 17h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j5qohtzrk {
  d: path("M6 7h10");
}

.mbmrpw-rs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v79iaqbup {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
