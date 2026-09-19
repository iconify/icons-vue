<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i39rm2bew"/><path class="lk3kqe07h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openbank" /></template>
<style>
.i39rm2bew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.58 28.043a3.96 3.96 0 0 1-7.92 0v-1.191");
}

.lk3kqe07h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.414 18.696a7.946 7.946 0 1 0 1.978 5.246l1.987-1.806H43.5v5.907a3.96 3.96 0 0 1-7.92 0v-1.191");
}

</style>
