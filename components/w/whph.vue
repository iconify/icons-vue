<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pqype0qiq"/><path class="k9ie3fb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:whph" /></template>
<style>
.k9ie3fb-m {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.121 23.211l5.134 5.134l11.122-11.121");
}

.pqype0qiq {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24A21.5 21.5 0 0 1 24 45.5A21.5 21.5 0 0 1 2.5 24A21.5 21.5 0 0 1 24 2.5A21.5 21.5 0 0 1 45.5 24");
}

</style>
