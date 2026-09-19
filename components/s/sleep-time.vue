<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGeicRMbIy" class="tqg48rb2f"/></defs><use href="#SVGeicRMbIy" class="c-zrgpb5l"/><use href="#SVGeicRMbIy" class="c-zrgpb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sleep-time" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tqg48rb2f {
  fill: none;
  stroke: currentColor;
  d: path("M39.839 38.533c-4.427 4.82-11.012 7.617-18.23 6.838c-9.8-1.058-17.748-8.887-18.944-18.67C1.408 16.41 7.455 7.314 16.308 3.924c.865-.331 1.694.58 1.254 1.394c-1.957 3.633-2.906 7.895-2.449 12.416c1.112 11.01 10.704 19.457 21.77 19.263q1.074-.019 2.12-.143c.922-.108 1.464.995.836 1.679");
}

</style>
