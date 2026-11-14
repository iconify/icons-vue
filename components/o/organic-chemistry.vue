<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ah-msqbxo"/><path class="pwbwyr30q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:organic-chemistry" /></template>
<style>
.ah-msqbxo {
  d: path("m12.75 6.932l5 2.885a1.5 1.5 0 0 1 .75 1.299v5.768a1.5 1.5 0 0 1-.75 1.299l-5 2.885a1.5 1.5 0 0 1-1.5 0l-5-2.885a1.5 1.5 0 0 1-.75-1.299v-5.768a1.5 1.5 0 0 1 .75-1.299l5-2.885a1.5 1.5 0 0 1 1.5 0M12 6.5v-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pwbwyr30q {
  d: path("M8.25 14a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
