<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n3jbjz9ky"/><path class="dqbhw_btk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rocket-alert" /></template>
<style>
.dqbhw_btk {
  d: path("m7.641 8.555l-1.403.128a1.5 1.5 0 0 0-.925.433l-.5.5a.708.708 0 0 0 .329 1.187l.791.198a1.5 1.5 0 0 0 1.425-.394l.847-.848a.707.707 0 0 0-.564-1.204m5.304 5.304l-.128 1.403a1.5 1.5 0 0 1-.433.925l-.5.5a.708.708 0 0 1-1.187-.329l-.198-.791a1.5 1.5 0 0 1 .394-1.425l.848-.847a.707.707 0 0 1 1.204.564M18 14.75v3.5M18 21h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n3jbjz9ky {
  d: path("m16.127 7.141l-.434 1.879a1.5 1.5 0 0 1-.401.724l-3.938 3.938a1.5 1.5 0 0 1-2.122 0l-1.414-1.414a1.5 1.5 0 0 1 0-2.122l3.938-3.938a1.5 1.5 0 0 1 .724-.401l1.879-.434a1.474 1.474 0 0 1 1.768 1.768");
}

</style>
