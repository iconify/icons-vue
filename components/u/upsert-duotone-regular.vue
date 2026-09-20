<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q46ar0blg"/><path class="ex75cacie"/><path class="htn9x-r-f"/><path class="sh_6_2bti"/><path class="j_oylnlgb"/><path class="e60x02nan"/><path class="yih0nfb7c"/><path class="xyj-l9cjp"/><path class="x_7wq3p0y"/><path class="c51p9nb2t"/><path class="nw0y-0bem"/><path class="vb93covwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:upsert-duotone-regular" /></template>
<style>
.c51p9nb2t {
  d: path("m6 6 3 3 3 -3");
}

.e60x02nan {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ex75cacie {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.htn9x-r-f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 3v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j_oylnlgb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nw0y-0bem {
  d: path("M17 3v4");
}

.q46ar0blg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 14h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sh_6_2bti {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 6 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vb93covwl {
  d: path("M15 5h4");
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

</style>
