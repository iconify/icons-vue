<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oilom4bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:retractable-leash" /></template>
<style>
.oilom4bxg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.581 7.581Q1.75 9.411 1.75 12t1.831 4.419Q5.411 18.25 8 18.25t4.419-1.831q1.56-1.559 1.791-3.669h1.545q.123 3 3.245 3q3.25 0 3.25-3.25v-1q0-1.346-.952-2.298T19 8.25q-3.122 0-3.245 3H14.21q-.231-2.11-1.791-3.669Q10.589 5.75 8 5.75T3.581 7.581M5.5 12q0-2.5 2.5-2.5t2.5 2.5T8 14.5T5.5 12");
}

</style>
