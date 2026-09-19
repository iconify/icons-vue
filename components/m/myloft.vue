<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mdrxxj3cu"/><path class="udfio9i1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myloft" /></template>
<style>
.mdrxxj3cu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.779 17.276V5.5l18.336 8.922l18.106-8.79V26");
}

.udfio9i1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.115 42.5L42.22 26l-8.627.067l-9.48 7.937L5.78 17.276v7.74z");
}

</style>
