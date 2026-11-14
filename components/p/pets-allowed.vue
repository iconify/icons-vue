<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp03yibgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pets-allowed" /></template>
<style>
.gp03yibgj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.422 2.639Q6.5 3.33 6.5 5.25q0 3 2.25 3t2.25-3t-2.25-3q-.81 0-1.328.389M13 5.25q0-1.92.922-2.611q.518-.389 1.328-.389q2.25 0 2.25 3t-2.25 3t-2.25-3M4.25 7.5Q2 7.5 2 10.25T4.25 13t2.25-2.75T4.25 7.5m13.25 2.75q0-2.75 2.25-2.75T22 10.25T19.75 13t-2.25-2.75m-5.5.5q2.829 0 5.124 2.597q2.126 2.405 2.126 4.903q0 1.86-1.428 2.812q-1.338.892-3.028.409q-.401-.112-1.071-.336q-1.155-.385-1.723-.385t-1.723.385q-.67.224-1.075.337q-1.686.482-3.024-.41Q4.75 20.11 4.75 18.25q0-2.498 2.126-4.903Q9.171 10.75 12 10.75");
}

</style>
