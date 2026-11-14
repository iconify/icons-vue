<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgkq2bb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:traffic-light-red" /></template>
<style>
.lgkq2bb1y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.25 1.25h-.5q-2.485 0-4.243 1.757Q5.75 4.765 5.75 7.25v9.5q0 2.485 1.757 4.243q1.758 1.757 4.243 1.757h.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-9.5q0-2.485-1.757-4.243Q14.735 1.25 12.25 1.25m-.25 2q3 0 3 3t-3 3t-3-3t3-3m0 7q2.25 0 2.25 2.25T12 14.75T9.75 12.5T12 10.25M9.75 18.5q0-2.25 2.25-2.25t2.25 2.25T12 20.75T9.75 18.5");
}

</style>
