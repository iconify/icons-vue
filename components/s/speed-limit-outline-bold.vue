<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r8vbx7bdh"/><path class="z475fobui"/><path class="mvkhxckkt"/><path class="jl9s5eill"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:speed-limit-outline-bold" /></template>
<style>
.jl9s5eill {
  d: path("M9.5 8.5 12 6");
}

.mvkhxckkt {
  d: path("M12 6v6");
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

.z475fobui {
  d: path("M12 16v6");
}

</style>
