<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejxtu1bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mammal" /></template>
<style>
.ejxtu1bwp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 5q0-3.25 2.5-3.25T11.25 5t-2.5 3.25T6.25 5m9-3.25q-2.5 0-2.5 3.25t2.5 3.25T17.75 5t-2.5-3.25M4 7.5q-2.5 0-2.5 3t2.5 3t2.5-3t-2.5-3m13.5 3q0-3 2.5-3t2.5 3t-2.5 3t-2.5-3m-5.5.75q2.494 0 4.669 2.297Q18.75 15.743 18.75 18q0 3.75-3.75 3.75q-.982 0-2.117-.494Q12.293 21 12 21t-.883.256Q9.982 21.75 9 21.75q-3.75 0-3.75-3.75q0-2.257 2.081-4.453Q9.506 11.25 12 11.25");
}

</style>
