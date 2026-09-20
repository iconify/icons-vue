<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y7uqdfbgj"/><path class="my8ijhbaa"/><path class="aw36cedja"/><path class="w7sxxlcqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:permission-grant-outline-thin" /></template>
<style>
.aw36cedja {
  d: path("M16 15h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.my8ijhbaa {
  d: path("M4 10a4 4 0 0 1 8 0");
}

.w7sxxlcqv {
  d: path("m18 12 3 3 -3 3");
}

.y7uqdfbgj {
  d: path("M2 12a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
