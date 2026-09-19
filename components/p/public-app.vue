<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="q9icox8la"/><circle class="s50phcb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:public-app" /></template>
<style>
.q9icox8la {
  cx: 18.339px;
  cy: 37.839px;
  r: 5.661px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s50phcb6d {
  cx: 24px;
  cy: 16.452px;
  r: 11.952px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
