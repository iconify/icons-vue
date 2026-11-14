<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tfcr4kbka"/><path class="ewblrupjm"/><path class="ihjmmjpky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:moraine" /></template>
<style>
.ewblrupjm {
  d: path("M10.5 17v-2.25a1.5 1.5 0 0 1 .6-1.2l2.848-2.136a1.5 1.5 0 0 1 1.225-.264l2.975.661a1.5 1.5 0 0 1 1.109 1.023l1.146 3.725a1.5 1.5 0 0 1-1.434 1.941H12a1.5 1.5 0 0 1-1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ihjmmjpky {
  d: path("m7.824 11.314l.974-3.574a1.5 1.5 0 0 1 .921-1.009l1.74-.653a1.5 1.5 0 0 1 1.974 1.01l.799 2.929a1.5 1.5 0 0 1-.547 1.594l-2.443 1.833a1.5 1.5 0 0 1-1.571.141L8.6 13.05a1.5 1.5 0 0 1-.776-1.736");
}

.tfcr4kbka {
  d: path("m3.466 16.636l.379-1.515a1.5 1.5 0 0 1 .711-.939l2.247-1.284a1.5 1.5 0 0 1 1.415-.039l1.453.726a1.5 1.5 0 0 1 .829 1.342V17A1.5 1.5 0 0 1 9 18.5H4.921a1.5 1.5 0 0 1-1.455-1.864");
}

</style>
