<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="avsermgoo"/><path class="utl7yebdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:u-turn-outline-bold" /></template>
<style>
.avsermgoo {
  d: path("M6 20v-9a6 6 0 0 1 12 0v9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.utl7yebdg {
  d: path("m15 17 3 3 3 -3");
}

</style>
