<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ebx45s03z"/><path class="a081khbzl"/><circle class="bhnurnc3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nudge-card" /></template>
<style>
.a081khbzl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.5 28.048c-3.689 6.525.357 8.237 2.723 4.46c.925-1.476 1.304-2.186 1.833-3.9");
}

.bhnurnc3d {
  cx: 43px;
  cy: 34.233px;
  r: 0.75px;
  fill: currentColor;
}

.ebx45s03z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.25 36.002c.413-21.352 19.87-37.775 15.978-7.1c-.66 5.207 2.79 10.971 8.83-4.05c-5.896 16.614 5.157 8.332 7.64.412");
}

</style>
