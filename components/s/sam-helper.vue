<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x096eu89c"/><circle class="wkxw5hbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sam-helper" /></template>
<style>
.wkxw5hbfm {
  cx: 24px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x096eu89c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27 24h14.26a1.24 1.24 0 0 0 1.24-1.24h0a9.25 9.25 0 0 0-18.332-1.752M21 24H6.74a1.24 1.24 0 0 0-1.24 1.24a9.25 9.25 0 0 0 18.336 1.735M24 27v14.25a1.24 1.24 0 0 0 1.23 1.25h.02a9.25 9.25 0 0 0 9.25-9.25h0a9.25 9.25 0 0 0-7.525-9.088M24 21V6.74a1.24 1.24 0 0 0-1.24-1.24h-.01a9.25 9.25 0 0 0-1.723 18.338");
}

</style>
