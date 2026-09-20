<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="li5ua4t9f"/><path class="ugrddxb0q"/><path class="v2mer508z"/><path class="t9gnp4b0n"/><path class="atsab9b_m"/><path class="qxhe48bjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:parasol-duotone-bold" /></template>
<style>
.atsab9b_m {
  d: path("M3 12q3 3 6 0 3 3 6 0 3 3 6 0");
}

.li5ua4t9f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qxhe48bjs {
  d: path("M12 14v7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t9gnp4b0n {
  d: path("M3 12a9 9 0 0 1 18 0");
}

.ugrddxb0q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12q3 3 6 0 3 3 6 0 3 3 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v2mer508z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 14v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
