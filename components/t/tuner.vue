<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="eovlm_9cu"/><path class="dlkoz2e6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tuner" /></template>
<style>
.dlkoz2e6w {
  d: path("M6.5 14a5.5 5.5 0 0 1 11 0M12 14l1.5-2.6M12 17.75v3.5m-3 0h6");
}

.eovlm_9cu {
  width: 16.5px;
  height: 13px;
  x: 3.75px;
  y: 4.75px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
