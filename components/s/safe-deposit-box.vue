<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-83kbb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:safe-deposit-box" /></template>
<style>
.i-83kbb4k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 3.25h11q1.76 0 3.005 1.245T21.75 7.5v9q0 1.76-1.245 3.005T17.5 20.75h-11q-1.76 0-3.005-1.245T2.25 16.5v-9q0-1.76 1.245-3.005T6.5 3.25M9 5.75H7Q4.75 5.75 4.75 8T7 10.25h2q2.25 0 2.25-2.25T9 5.75m6 0q-2.25 0-2.25 2.25T15 10.25h2q2.25 0 2.25-2.25T17 5.75zm-6 5H7q-2.25 0-2.25 2.25T7 15.25h2q2.25 0 2.25-2.25T9 10.75m6 0q-2.25 0-2.25 2.25T15 15.25h2q2.25 0 2.25-2.25T17 10.75zm-6 5H7q-2.25 0-2.25 2.25T7 20.25h2q2.25 0 2.25-2.25T9 15.75m6 0q-2.25 0-2.25 2.25T15 20.25h2q2.25 0 2.25-2.25T17 15.75z");
}

</style>
