<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf1yxhmja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:phone-classic" /></template>
<style>
.xf1yxhmja {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 9V7.5q0-2.002 3.373-3.206Q8.045 3.25 12 3.25t6.877 1.044Q22.25 5.498 22.25 7.5V9q0 1.75-1.75 1.75h-2q-1.75 0-1.75-1.75v-.75h-9.5V9q0 1.75-1.75 1.75h-2q-1.75 0-1.75-1.75m17.542 5.118q-.74-2.368-3.222-2.368H7.93q-2.482 0-3.222 2.368l-.859 2.75q-.509 1.63.502 3.006t2.72 1.376h9.858q1.708 0 2.72-1.376q1.011-1.376.502-3.006zM12 13.75q2.75 0 2.75 2.75T12 19.25T9.25 16.5T12 13.75m0 4q-1.25 0-1.25-1.25T12 15.25t1.25 1.25T12 17.75");
}

</style>
