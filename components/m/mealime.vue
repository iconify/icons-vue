<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lou_vkerr"/><path class="qctj9e1cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mealime" /></template>
<style>
.lou_vkerr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.923 4.5l21.561 36.69l.004-.004a21.2 21.2 0 0 1-9.653 2.314c-11.772 0-21.323-9.55-21.323-21.323c0-7.349 3.73-13.842 9.408-17.674zm7.86 32.35l2.92-14.005m-11.688 6.76l11.688-6.76m-13.21-3.807l13.21 3.807");
}

.qctj9e1cv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.392 6.999L38.016 38.69l.003-.003a18.3 18.3 0 0 1-8.337 1.999c-10.169 0-18.418-8.25-18.418-18.418c0-6.348 3.222-11.956 8.126-15.267z");
}

</style>
