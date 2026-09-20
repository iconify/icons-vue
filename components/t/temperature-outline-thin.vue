<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rxj7i8-nj"/><path class="vt7vyubju"/><path class="vymzkpbdz"/><path class="e2aybg2ii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:temperature-outline-thin" /></template>
<style>
.e2aybg2ii {
  d: path("M14.5 12H18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rxj7i8-nj {
  d: path("M9 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.vt7vyubju {
  d: path("M12 4v11");
}

.vymzkpbdz {
  d: path("M14.5 8H18");
}

</style>
