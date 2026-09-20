<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wrdzdhojp"/><path class="hf_gtezns"/><path class="q7i-7h40d"/><path class="ickqm6bom"/><path class="z1qzf1gcm"/><path class="wtli1rzwt"/><path class="yih0nfb7c"/><path class="xyj-l9cjp"/><path class="x_7wq3p0y"/><path class="c51p9nb2t"/><path class="nw0y-0bem"/><path class="vb93covwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:upsert-duotone-thin" /></template>
<style>
.c51p9nb2t {
  d: path("m6 6 3 3 3 -3");
}

.hf_gtezns {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ickqm6bom {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 6 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nw0y-0bem {
  d: path("M17 3v4");
}

.q7i-7h40d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vb93covwl {
  d: path("M15 5h4");
}

.wrdzdhojp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 14h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wtli1rzwt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x_7wq3p0y {
  d: path("M9 3v5");
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

.yih0nfb7c {
  d: path("M3 14h18");
}

.z1qzf1gcm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
