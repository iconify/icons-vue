<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k4nfprbzz"/><path class="dem7zwy2d"/><path class="m8ef0m9xo"/><path class="ov5pw4sxv"/><path class="p8zr033kc"/><path class="lkej6mbow"/><path class="qv6cnabrq"/><path class="oqj-o0b2r"/><path class="ktxjg3b2q"/><path class="evsu0jbbm"/><path class="drjad9bfe"/><path class="zpusjcvvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rake-duotone-bold" /></template>
<style>
.dem7zwy2d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 14h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.drjad9bfe {
  d: path("M14 14v4");
}

.evsu0jbbm {
  d: path("M10 14v4");
}

.k4nfprbzz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ktxjg3b2q {
  d: path("M6 14v4");
}

.lkej6mbow {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m8ef0m9xo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oqj-o0b2r {
  d: path("M5 14h14");
}

.ov5pw4sxv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p8zr033kc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qv6cnabrq {
  d: path("M12 3v11");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zpusjcvvn {
  d: path("M18 14v4");
}

</style>
