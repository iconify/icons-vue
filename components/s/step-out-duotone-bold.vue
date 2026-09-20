<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h2sq3fbpa"/><path class="x47b2wbqm"/><path class="vj17dpbln"/><path class="xyj-l9cjp"/><path class="ilxguy6uu"/><path class="t407nkbfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:step-out-duotone-bold" /></template>
<style>
.h2sq3fbpa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ilxguy6uu {
  d: path("M12 4v10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t407nkbfi {
  d: path("m9 7 3 -3 3 3");
}

.vj17dpbln {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 7 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x47b2wbqm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
