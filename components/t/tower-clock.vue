<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g8gr5f-ht"/><circle class="i51s6__iq"/><path class="b00gw5bul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tower-clock" /></template>
<style>
.b00gw5bul {
  d: path("M12 11.25v1.25l.75.75m-2 8V19.5a1.25 1.25 0 0 1 2.5 0v1.75");
}

.g8gr5f-ht {
  d: path("M7 20.5V9.75q0-.75.48-1.33l.29-.34q.48-.58.94-1.17l2.83-3.57q.46-.59.92 0l2.83 3.57q.46.59.94 1.17l.29.34Q17 9 17 9.75V20.5q0 .75-.75.75h-8.5q-.75 0-.75-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i51s6__iq {
  cx: 12px;
  cy: 12.5px;
  r: 2.5px;
}

</style>
