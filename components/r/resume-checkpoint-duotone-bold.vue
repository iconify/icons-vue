<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oyx_crbik"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="gjqclrbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:resume-checkpoint-duotone-bold" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.gjqclrbty {
  d: path("m10.5 7 3 3 -3 3Z");
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.oyx_crbik {
  fill: currentColor;
  d: path("m10.5 7 3 3 -3 3Z");
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

</style>
