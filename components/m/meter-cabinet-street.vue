<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v_rw1ryin"/><path class="leiaoeb5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meter-cabinet-street" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.leiaoeb5v {
  d: path("M6.75 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M14.5 7H17m-2.5 3H17");
}

.v_rw1ryin {
  d: path("M7.125 2.5h9.75A2.625 2.625 0 0 1 19.5 5.125v10.25A2.625 2.625 0 0 1 16.875 18h-9.75A2.625 2.625 0 0 1 4.5 15.375V5.125A2.625 2.625 0 0 1 7.125 2.5M8 18v3.5h8V18M12 2.5V18");
}

</style>
