<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzpqnlmob"/><path class="gq9l41c4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zero" /></template>
<style>
.gq9l41c4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.872 24.788a2.25 2.25 0 0 1 2.25-2.25m-2.25 0V28.5m-14.162-9h5.963l-5.963 9h5.963m5.683-1.135a2.25 2.25 0 0 1-4.205-1.115v-1.462a2.25 2.25 0 0 1 4.5 0v.73h-4.5m10.639-.73a2.25 2.25 0 0 1 4.5 0v1.462a2.25 2.25 0 0 1-4.5 0z");
}

.hzpqnlmob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4");
}

</style>
