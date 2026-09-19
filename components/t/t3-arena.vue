<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cewl31b3j"/><path class="k6pucybve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:t3-arena" /></template>
<style>
.cewl31b3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.994 27.835h7.25m-5.906-7.67h7.249m-8.832-7.23l-1.157 6.607a.53.53 0 0 0 .523.623h2.217l-1.344 7.67h-2.403a.53.53 0 0 0-.523.44l-1.158 6.607a.53.53 0 0 0 .524.623h16.69a.53.53 0 0 0 .523-.44l3.845-21.947a.53.53 0 0 0-.523-.623h-16.69a.53.53 0 0 0-.524.44");
}

.k6pucybve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.2 12.495H6.19a.53.53 0 0 0-.524.44l-1.158 6.607a.53.53 0 0 0 .524.623h5.577L8.03 34.882a.53.53 0 0 0 .524.623h6.59a.53.53 0 0 0 .524-.44l2.61-14.9h5.764a.53.53 0 0 0 .523-.44l1.158-6.607a.53.53 0 0 0-.524-.623Z");
}

</style>
