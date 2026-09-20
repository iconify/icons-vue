<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_nq2o9vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:search-check-2-outline-sharp" /></template>
<style>
.a_nq2o9vi {
  fill: currentColor;
  d: path("M14.25 14.25Q16 12.5 16 10t-1.75-4.25T10 4T5.75 5.75T4 10t1.75 4.25T10 16t4.25-1.75m-5.3-.7l5.65-5.675l-1.425-1.425L8.95 10.7L6.825 8.6L5.4 10zM10 18q-3.35 0-5.675-2.325T2 10t2.325-5.675T10 2t5.675 2.325T18 10q0 1.4-.437 2.638T16.325 14.9L22 20.6L20.6 22l-5.7-5.675q-1.025.8-2.262 1.238T10 18m0-8");
}

</style>
