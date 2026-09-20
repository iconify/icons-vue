<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="i4ln5bb6z"/><path class="srcz9izvv"/><path class="z5rak8b7e"/><path class="xgrfb-bqu"/><path class="w8fmvxwit"/><path class="r3-lax2ik"/><path class="fu2iodbya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mmr-duotone-bold" /></template>
<style>
.fu2iodbya {
  d: path("M3 16h16");
}

.i4ln5bb6z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.khksl7boy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3-lax2ik {
  d: path("m8 9 4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.srcz9izvv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 9 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w8fmvxwit {
  d: path("M3 11h14");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.z5rak8b7e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
