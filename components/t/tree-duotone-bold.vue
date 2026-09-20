<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bcockwbin"/><path class="r8vbx7bdh"/><path class="vhf3_kexp"/><path class="gl3o38_gx"/><path class="x4l9y4bgo"/><path class="hvp96bbhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tree-duotone-bold" /></template>
<style>
.bcockwbin {
  fill: currentColor;
  d: path("M5 9a7 7 0 1 0 14 0A7 7 0 1 0 5 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gl3o38_gx {
  d: path("M8 21h8");
}

.hvp96bbhp {
  d: path("m12 18 4 -4");
}

.r8vbx7bdh {
  d: path("M5 9a7 7 0 1 0 14 0A7 7 0 1 0 5 9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vhf3_kexp {
  d: path("M12 16v5");
}

.x4l9y4bgo {
  d: path("m12 16 -4 -4");
}

</style>
