<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qa3aibc9w"/><path class="b4ckndyks"/><path class="zm8pwrbun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-head-down" /></template>
<style>
.b4ckndyks {
  d: path("M12.5 7.5c-2.25 1.5-2.75 4-2 7m-1.5 7l1.5-7l2 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qa3aibc9w {
  d: path("M12 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.zm8pwrbun {
  d: path("m11.25 8.75l2.75 3.5l.5 2.75");
}

</style>
