<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r7bsc7b6t"/><path class="wh_hh0ljm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reputation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r7bsc7b6t {
  d: path("M5.5 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

.wh_hh0ljm {
  d: path("M8.5 15v6l1.75-1.25L12 21l1.75-1.25L15.5 21v-6m-3.125-7.875l.068.203a1.5 1.5 0 0 0 1.274 1.019l.386.038a.493.493 0 0 1 .272.865l-.192.164a1.5 1.5 0 0 0-.488 1.465l.055.246a.483.483 0 0 1-.727.514l-.228-.142a1.5 1.5 0 0 0-1.59 0l-.228.142a.483.483 0 0 1-.727-.514l.055-.246a1.5 1.5 0 0 0-.488-1.465l-.192-.164a.493.493 0 0 1 .272-.865l.386-.038a1.5 1.5 0 0 0 1.274-1.019l.068-.203a.395.395 0 0 1 .75 0");
}

</style>
