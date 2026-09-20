<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uw2t0mbce"/><path class="plo1k7bci"/><path class="mnwr0qhch"/><path class="h3z-uye4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:straight-ahead-duotone-bold" /></template>
<style>
.h3z-uye4u {
  d: path("m8 8 4 -4 4 4");
}

.mnwr0qhch {
  d: path("M12 4v17");
}

.plo1k7bci {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 8 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uw2t0mbce {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
