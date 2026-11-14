<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="isd6t_bew"/><path class="wo5i-gbel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:staff-task-list" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.isd6t_bew {
  d: path("M6.625 4.5h10.75A2.625 2.625 0 0 1 20 7.125v11.75a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 18.875V7.125A2.625 2.625 0 0 1 6.625 4.5M8 2.5v4m4-4v4m4-4v4");
}

.wo5i-gbel {
  d: path("m6.75 11.25l1 1l2-2m2.25 1h5M8.25 15za1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5M12 16.5h5");
}

</style>
