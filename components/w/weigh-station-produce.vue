<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zdynzxbin"/><path class="agwi4rn2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:weigh-station-produce" /></template>
<style>
.agwi4rn2b {
  d: path("M16.931 14.5h2.138a1.5 1.5 0 0 1 1.458 1.148l1.026 4.25a1.5 1.5 0 0 1-1.458 1.852h-4.19a1.5 1.5 0 0 1-1.458-1.852l1.026-4.25a1.5 1.5 0 0 1 1.458-1.148M18 17h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdynzxbin {
  d: path("M19.997 11.766Q20 11.634 20 11.5c0-6-5.5-6-8-4.5c-2.5-1.5-8-1.5-8 4.5c0 5 3 9 5.5 9c1.014 0 1.534-.493 2.094-.68M12 7l.5-3.5M13 5c.75-2 2.5-2.5 4-2c-.5 1.75-2.25 2.5-4 2");
}

</style>
