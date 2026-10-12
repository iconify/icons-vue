<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="e51f8ryyj"/><path class="k0ohffixm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-falling" /></template>
<style>
.e51f8ryyj {
  cx: 6.5px;
  cy: 8px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0ohffixm {
  d: path("M12.5 14L9 10.5m1 1l-3.25 3.75l-.75 3m4-6.75l4.25-2.75M12.5 14l4.5-1.5l1.75 2.75M12.5 14l2.5 3.75l3.75-.25M7.3 3.55a4.5 4.5 0 0 1 3.3 2.55M3 20.75h18");
}

</style>
