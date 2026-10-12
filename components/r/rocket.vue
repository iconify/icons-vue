<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tuceotbwy"/><circle class="sapxmnb0l"/><path class="eiu3qebmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rocket" /></template>
<style>
.eiu3qebmn {
  d: path("M12 18.75v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sapxmnb0l {
  cx: 12px;
  cy: 10.5px;
  r: 2px;
}

.tuceotbwy {
  d: path("M12 2.75c3 2 4.5 5 4.5 8.75v5h-9v-5C7.5 7.75 9 4.75 12 2.75m-4.5 9l-2.25 2.5V18l2.25-1.5m9-4.75l2.25 2.5V18l-2.25-1.5");
}

</style>
