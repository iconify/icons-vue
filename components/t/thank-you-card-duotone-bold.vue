<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ybjj6ac-t"/><path class="oih3pvykm"/><path class="cnjkjfbvs"/><path class="b2-xg2rvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:thank-you-card-duotone-bold" /></template>
<style>
.b2-xg2rvm {
  d: path("M12 16c-3 -2 -6 -4.5 -4.5 -7C9 7.5 11 8.5 12 10c1 -1.5 3 -2.5 4.5 -1 1.5 2.5 -1.5 5 -4.5 7");
}

.cnjkjfbvs {
  d: path("M3 5v14h18V5Z");
}

.oih3pvykm {
  fill: currentColor;
  d: path("M12 16c-3 -2 -6 -4.5 -4.5 -7C9 7.5 11 8.5 12 10c1 -1.5 3 -2.5 4.5 -1 1.5 2.5 -1.5 5 -4.5 7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ybjj6ac-t {
  fill: currentColor;
  d: path("M3 5v14h18V5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
