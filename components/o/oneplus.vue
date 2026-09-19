<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q6djenbqv"/><path class="hkkqtpc7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oneplus" /></template>
<style>
.hkkqtpc7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.508 20.109a4.19 4.19 0 0 1-4.191 4.192h0");
}

.q6djenbqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.222 20.109V6.5m-7.331 6.278H44.5m-6.278 11.876V41.5H9.5V12.778h16.846m-1.838 21.816V20.109");
}

</style>
