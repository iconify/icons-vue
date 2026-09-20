<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ap4y97b6y"/><path class="tqb1r-way"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:noodles-and-company" /></template>
<style>
.ap4y97b6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.429 33.507l-.775-2.89a6.489 6.489 0 0 1 12.535-3.359s.775 2.892.775 2.892");
}

.tqb1r-way {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.895 36.868c-.428-1.598 2.03-3.645 5.492-4.572c3.462-.928 6.615-.384 7.043 1.213c.428 1.598-2.031 3.645-5.492 4.572c-3.462.928-6.615.384-7.043-1.213l-.775-2.893C2.337 23.591 8.5 12.917 18.884 10.135s21.058 3.38 23.84 13.763l.776 2.893c.428 1.598-2.031 3.645-5.492 4.572c-3.462.928-6.615.384-7.043-1.213c-.428-1.598 2.03-3.645 5.492-4.572c3.462-.928 6.615-.385 7.043 1.213");
}

</style>
