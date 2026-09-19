<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z646vlbvs"/><path class="c8hclmszh"/><path class="hu_w-tbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skiinfo" /></template>
<style>
.c8hclmszh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.131 20.34s12.12-7.018 15.806-10.066c4.181 4.394 18.215 9.569 18.215 9.569l-5.67-1.347L38.6 21.12l-12.191-4.607l-.071 2.835l-3.26-3.899l-1.914 2.481l-2.339-.709l-3.969 2.765l1.347-2.977z");
}

.hu_w-tbxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.963 34.657c-4.714-8.754 4.027-11.27 5.28-11.27c9.356-.425 13.212-1.506 11.228-4.696c8.893 6.676-9.086 4.21-8.222 7.706c1.772 4.891 10.349 7.089 10.349 7.089m2.559-22.729l.684 1.725l-1.723.077m4.851-.709l-1.824.342l.254-1.706m.694 5.001l-.733-1.705l1.72-.126m-4.816.936l1.775-.54l-.065 1.724");
}

.z646vlbvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 10.24c.061 21.93 18.439 31.977 18.439 31.977S42.5 32.18 42.5 10.24c-16.11-6.003-21.256-5.881-36.999 0z");
}

</style>
