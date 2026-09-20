<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qn-h03e3f"/><path class="aekq9_1ic"/><path class="xo596rbbf"/><path class="crv4i00bu"/><path class="f3r6jjb4a"/><path class="q_47v4dkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quality-gate-duotone-bold" /></template>
<style>
.aekq9_1ic {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.crv4i00bu {
  d: path("M4 3v18");
}

.f3r6jjb4a {
  d: path("M20 3v18");
}

.q_47v4dkd {
  d: path("m8 12 3 3 6 -6");
}

.qn-h03e3f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xo596rbbf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 12 3 3 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
