<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t8m10-b0v"/><path class="ylywc-zmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simplemind-lite" /></template>
<style>
.t8m10-b0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5V24A18.5 18.5 0 0 0 24 42.5A18.5 18.5 0 0 0 42.5 24A18.5 18.5 0 0 0 24 5.5z");
}

.ylywc-zmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.083 12.083V24A11.917 11.917 0 0 0 24 35.917A11.917 11.917 0 0 0 35.917 24A11.917 11.917 0 0 0 24 12.083z");
}

</style>
