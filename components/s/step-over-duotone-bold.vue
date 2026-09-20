<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h2sq3fbpa"/><path class="mbte3jbps"/><path class="uznwvsb7r"/><path class="xyj-l9cjp"/><path class="ilnpzmblt"/><path class="b1o8mue8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:step-over-duotone-bold" /></template>
<style>
.b1o8mue8c {
  d: path("m15 11 3 3 3 -3");
}

.h2sq3fbpa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ilnpzmblt {
  d: path("M6 14a6 6 0 0 1 12 0");
}

.mbte3jbps {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uznwvsb7r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 11 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
