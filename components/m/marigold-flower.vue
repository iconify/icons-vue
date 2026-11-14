<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qnhxhr4qx"/><path class="xe-923b2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marigold-flower" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qnhxhr4qx {
  d: path("M12.612 3.319za1.2 1.2 0 0 0 1.519.347a.764.764 0 0 1 1.102.531a1.2 1.2 0 0 0 1.218.971a.764.764 0 0 1 .763.957a1.2 1.2 0 0 0 .676 1.403a.764.764 0 0 1 .272 1.193a1.2 1.2 0 0 0 0 1.558a.764.764 0 0 1-.272 1.193a1.2 1.2 0 0 0-.676 1.403a.764.764 0 0 1-.763.957a1.2 1.2 0 0 0-1.218.971a.764.764 0 0 1-1.102.531a1.2 1.2 0 0 0-1.519.347a.764.764 0 0 1-1.224 0a1.2 1.2 0 0 0-1.519-.347a.764.764 0 0 1-1.102-.531a1.2 1.2 0 0 0-1.218-.971a.764.764 0 0 1-.763-.957a1.2 1.2 0 0 0-.676-1.403a.764.764 0 0 1-.272-1.193a1.2 1.2 0 0 0 0-1.558a.764.764 0 0 1 .272-1.193a1.2 1.2 0 0 0 .676-1.403a.764.764 0 0 1 .763-.957a1.2 1.2 0 0 0 1.218-.971a.764.764 0 0 1 1.102-.531a1.2 1.2 0 0 0 1.519-.347a.764.764 0 0 1 1.224 0M12 16.5v5");
}

.xe-923b2y {
  d: path("M9.5 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M12 20c-3 0-4.5-1.5-4.5-3.5c2.5 0 4 1.25 4.5 3.5");
}

</style>
