<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi7hllbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:money-pool" /></template>
<style>
.yi7hllbtt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.288 4.538Q6.75 6.075 6.75 8.25q0 1.379.618 2.501q-2.089.046-3.58 1.537Q2.25 13.825 2.25 16t1.538 3.712Q5.325 21.25 7.5 21.25t3.712-1.538q.464-.463.787-.984q.324.522.788.986q1.538 1.538 3.713 1.538t3.713-1.538Q21.751 18.175 21.75 16q.001-2.175-1.537-3.714q-1.49-1.491-3.58-1.537q.617-1.122.617-2.499q0-2.175-1.538-3.712Q14.175 3 12 3T8.288 4.538M9.5 8.25q0-2.5 2.5-2.5q1.036 0 1.768.732T14.5 8.25t-.732 1.768T12 10.75q-2.5 0-2.5-2.5M5 16q0-2.5 2.5-2.5q1.036 0 1.768.732T10 16t-.732 1.768T7.5 18.5Q5 18.5 5 16m11.5-2.5q2.5 0 2.5 2.5t-2.5 2.5T14 16t2.5-2.5");
}

</style>
