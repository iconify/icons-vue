<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wpsfqhbyw"/><path class="vtk3i1brc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reward-badge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vtk3i1brc {
  d: path("M13.75 10.25C13.5 9.5 12.9 9 12 9c-1.05 0-1.75.6-1.75 1.5c0 1.6 3.5.9 3.5 3c0 .9-.75 1.5-1.75 1.5c-.9 0-1.55-.4-1.75-1M12 7.75V9m0 6v1.25");
}

.wpsfqhbyw {
  d: path("m13.068 3.141l.29.242a2.19 2.19 0 0 0 1.775.475l.372-.064a1.67 1.67 0 0 1 1.849 1.067l.131.355a2.19 2.19 0 0 0 1.299 1.299l.355.131a1.67 1.67 0 0 1 1.067 1.849l-.064.372a2.19 2.19 0 0 0 .475 1.775l.242.29a1.67 1.67 0 0 1 0 2.136l-.242.29a2.19 2.19 0 0 0-.475 1.775l.064.372a1.67 1.67 0 0 1-1.067 1.849l-.355.131a2.19 2.19 0 0 0-1.299 1.299l-.131.355a1.67 1.67 0 0 1-1.849 1.067l-.372-.064a2.19 2.19 0 0 0-1.775.475l-.29.242a1.67 1.67 0 0 1-2.136 0l-.29-.242a2.19 2.19 0 0 0-1.775-.475l-.372.064a1.67 1.67 0 0 1-1.849-1.067l-.131-.355a2.19 2.19 0 0 0-1.299-1.299l-.355-.131a1.67 1.67 0 0 1-1.067-1.849l.064-.372a2.19 2.19 0 0 0-.475-1.775l-.242-.29a1.67 1.67 0 0 1 0-2.136l.242-.29a2.19 2.19 0 0 0 .475-1.775l-.064-.372a1.67 1.67 0 0 1 1.067-1.849l.355-.131a2.19 2.19 0 0 0 1.299-1.299l.131-.355a1.67 1.67 0 0 1 1.849-1.067l.372.064a2.19 2.19 0 0 0 1.775-.475l.29-.242a1.67 1.67 0 0 1 2.136 0");
}

</style>
