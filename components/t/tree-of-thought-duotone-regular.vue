<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j93aodlin"/><path class="qd8vi3lre"/><path class="im38brk4q"/><path class="mxj5oeb5r"/><path class="w8mha9b3t"/><path class="ahj6w3fjq"/><path class="l2x-_sd5q"/><path class="zesf2kblt"/><path class="uxyzhxvwz"/><path class="f4wf9tbjy"/><path class="zy54a7bml"/><path class="t7ql4f28h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tree-of-thought-duotone-regular" /></template>
<style>
.ahj6w3fjq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f4wf9tbjy {
  d: path("m7 14 5 5h5");
}

.im38brk4q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j93aodlin {
  fill: currentColor;
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l2x-_sd5q {
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.mxj5oeb5r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 14 5 5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qd8vi3lre {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 10 5 -5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t7ql4f28h {
  d: path("m19 10 2 2 -2 2");
}

.uxyzhxvwz {
  d: path("M7 12h10");
}

.w8mha9b3t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zesf2kblt {
  d: path("m7 10 5 -5h5");
}

.zy54a7bml {
  d: path("M17 12h4");
}

</style>
