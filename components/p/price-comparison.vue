<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smj_grbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:price-comparison" /></template>
<style>
.smj_grbog {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.409 5.031l2.5-2.5q.659-.66 1.591-.66t1.592.66l2.499 2.5q.659.659.659 1.59V19.5q0 2.25-2.25 2.25h-5q-2.25 0-2.25-2.25V6.621q0-.931.659-1.59M15.75 6.75q0 1.75 1.75 1.75t1.75-1.75T17.5 5t-1.75 1.75M4.909 6.531l-2.5 2.5q-.659.659-.659 1.59V19.5q0 2.25 2.25 2.25h5q2.25 0 2.25-2.25v-8.879q0-.931-.659-1.59l-2.5-2.5q-.659-.66-1.591-.66t-1.591.66M6.5 9q1.75 0 1.75 1.75T6.5 12.5t-1.75-1.75T6.5 9");
}

</style>
