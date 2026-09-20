<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lgxr2mbgu"/><path class="iy4y_h83n"/><path class="b_jvulbrc"/><path class="zfck_bu1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:table-lock-outline-thin" /></template>
<style>
.b_jvulbrc {
  d: path("M7 18a3 3 0 0 1 3 -3h4a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-4a3 3 0 0 1 -3 -3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iy4y_h83n {
  d: path("M2 6.5h20");
}

.lgxr2mbgu {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.zfck_bu1o {
  d: path("M8.5 15a3.5 3.5 0 0 1 7 0");
}

</style>
