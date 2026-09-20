<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="our76je3d"/><path class="l8dn9jbyp"/><path class="x963bozsy"/><path class="l0nc5l-lx"/><path class="mq159kbup"/><path class="sfp0ggbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stress-level-duotone-bold" /></template>
<style>
.l0nc5l-lx {
  d: path("M6 15v3");
}

.l8dn9jbyp {
  d: path("M2 15h20");
}

.mq159kbup {
  d: path("M12 15v3");
}

.our76je3d {
  fill: currentColor;
  d: path("m12 8 4 4H8Z");
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

.sfp0ggbri {
  d: path("M18 15v3");
}

.x963bozsy {
  d: path("m12 8 4 4H8Z");
}

</style>
