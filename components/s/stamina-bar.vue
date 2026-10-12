<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uk_4fqdsc"/><rect class="q3-s69i3m"/><rect class="s7vrle9ca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stamina-bar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q3-s69i3m {
  width: 10.5px;
  height: 7.5px;
  x: 10.75px;
  y: 8.25px;
  rx: 2px;
}

.s7vrle9ca {
  width: 5.5px;
  height: 2.5px;
  x: 13.25px;
  y: 10.75px;
  rx: 0.75px;
}

.uk_4fqdsc {
  d: path("m6.22 9.28l-2.94 2.94q-.28.28.12.28h1.7q.4 0 .25.37l-.7 1.76q-.15.37.11.07l2.73-3.15q.26-.3-.14-.3h-1.7q-.4 0-.21-.35l.87-1.55q.19-.35-.09-.07");
}

</style>
