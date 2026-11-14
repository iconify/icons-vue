<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xqehlac9k"/><path class="p-wf3yb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:waste-rock-dump" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p-wf3yb0o {
  fill: currentColor;
  d: path("M15.125 6.125za1.186 1.186 0 0 1 1.5.75a1.186 1.186 0 0 1-.75 1.5a1.186 1.186 0 0 1-1.5-.75a1.186 1.186 0 0 1 .75-1.5m2.5 5.375za1.23 1.23 0 0 1 1.625.625a1.23 1.23 0 0 1-.625 1.625A1.23 1.23 0 0 1 17 13.125a1.23 1.23 0 0 1 .625-1.625m.5 7.5l.15-.601a1.5 1.5 0 0 1 1.13-1.1l.22-.049a1.144 1.144 0 0 1 1.366.877l.134.623a1.447 1.447 0 0 1-1.415 1.75h-.414a1.207 1.207 0 0 1-1.171-1.5");
}

.xqehlac9k {
  d: path("M3 20.5L8.75 4L15 20.5m-12.5 0h19");
}

</style>
