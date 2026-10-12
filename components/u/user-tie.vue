<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="i2q79lhiz"/><path class="xl-47pbkh"/><path class="r2qwgtbvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-tie" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2q79lhiz {
  cx: 12px;
  cy: 6.75px;
  r: 3.5px;
}

.r2qwgtbvy {
  d: path("m12.21 15.09l.98 1.57q.21.34-.02.67l-.94 1.34q-.23.33-.46 0l-.94-1.34q-.23-.33-.02-.67l.98-1.57q.21-.34.42 0");
}

.xl-47pbkh {
  d: path("M5.25 20.25h13.5a.75.75 0 0 0 .75-.75c0-3.6-3.38-6.5-7.5-6.5s-7.5 2.9-7.5 6.5a.75.75 0 0 0 .75.75");
}

</style>
