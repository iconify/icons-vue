<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="hv1go2bhw"/><path class="ypqu64byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:osmand-plus" /></template>
<style>
.hv1go2bhw {
  cx: 24.088px;
  cy: 22.074px;
  r: 11.687px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ypqu64byo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.754 3.196C12.661 4.804 6.428 11.316 5 17.46c-2.534 10.4 3.737 20.912 14.094 23.622a3 3 0 0 1 1.398.87l3.236 3.405a.5.5 0 0 0 .7 0l3.246-3.406c.38-.412.868-.71 1.408-.859C39.547 38.24 45.718 27.445 42.866 16.98S29.22.344 18.754 3.196m.839 18.878h8.99m-4.495-4.495v8.99");
}

</style>
