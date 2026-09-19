<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j9rfgbbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xpark" /></template>
<style>
.j9rfgbbgs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.279 25.347h-1.467l-1.044-2.065L42.5 9.186l-11.155-.001l-5.604 6.988l-2.977-6.988h-10.42l6.634 13.647l-2.376 2.514h1.627L5.5 38.816h11.468l7.476-9.052l3.864 9.051h10.783z");
}

</style>
