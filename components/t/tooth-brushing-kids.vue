<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nd2ms8bth"/><path class="ke1k8c5cj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-brushing-kids" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ke1k8c5cj {
  d: path("M13 5.5L15.5 8l-3.25 3.25l-2.5-2.5Zm1.25 1.25l4.5-4.5m-.486 12.792l.166.335a1.5 1.5 0 0 0 1.129.821l.37.053a.574.574 0 0 1 .318.979l-.268.26a1.5 1.5 0 0 0-.431 1.328l.063.368a.574.574 0 0 1-.832.605l-.331-.174a1.5 1.5 0 0 0-1.396 0l-.331.174a.574.574 0 0 1-.832-.605l.063-.368a1.5 1.5 0 0 0-.431-1.328l-.268-.26a.574.574 0 0 1 .318-.979l.37-.053a1.5 1.5 0 0 0 1.129-.821l.166-.335a.574.574 0 0 1 1.028 0");
}

.nd2ms8bth {
  d: path("M10.963 3.599c-.83.203-1.497.651-2.463.651c-1.25 0-2-.75-3.25-.75C3.5 3.5 2.5 5 2.5 7c0 2.5.75 3.5 1.25 5.25L4.5 17c.25 1.25 1.75 1.25 2 0l.75-3.25h2.5L10.5 17c.209 1.046 1.294 1.217 1.789.512m.531-2.539l.156-.988");
}

</style>
