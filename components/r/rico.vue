<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ysrv3-b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rico" /></template>
<style>
.ysrv3-b4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.289 18.353c-3.155-3.119-8.269-3.119-11.424 0a7.923 7.923 0 0 0 0 11.294c3.155 3.119 8.269 3.119 11.423 0l11.423-11.294c3.155-3.119 8.269-3.119 11.424 0a7.923 7.923 0 0 1 0 11.294c-3.155 3.119-8.269 3.119-11.423 0L24 24");
}

</style>
