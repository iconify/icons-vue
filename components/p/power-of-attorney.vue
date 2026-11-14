<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u4e32pf5x"/><path class="id3ot5oxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:power-of-attorney" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.id3ot5oxn {
  d: path("M6.5 6V3h7v3M10 21.5V14m-1.5-1.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M16.25 16a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-1.75 5.75a3.5 3 0 0 1 7 0");
}

.u4e32pf5x {
  d: path("m13.46 15.838l-2.18 3.568q-.025.041-.053.08t-.057.077t-.062.073t-.067.068t-.071.064t-.075.06t-.079.055t-.082.049t-.085.044q-.043.021-.088.039q-.044.018-.09.033q-.045.015-.092.027q-.046.012-.093.021t-.095.016t-.095.009t-.096.003t-.096-.003t-.095-.009t-.095-.016q-.047-.009-.093-.021q-.047-.012-.092-.027q-.046-.015-.09-.033q-.045-.018-.088-.039q-.043-.02-.085-.044t-.082-.049q-.04-.026-.079-.055q-.038-.029-.075-.06q-.036-.031-.071-.064t-.067-.068q-.032-.036-.062-.073q-.03-.038-.057-.077t-.053-.08l-3.867-6.329q-.083-.136-.136-.286q-.053-.151-.072-.309q-.02-.158-.007-.317t.061-.311l1.475-4.795q.035-.114.088-.222q.053-.107.122-.204q.069-.098.153-.183q.083-.086.18-.157t.202-.126q.106-.054.22-.092q.113-.037.231-.056T7.608 6h4.784q.12 0 .238.019t.231.056q.114.038.22.092q.106.055.202.126t.18.157t.153.183t.122.204q.053.108.088.222l1.475 4.795q.071.231.066.473");
}

</style>
