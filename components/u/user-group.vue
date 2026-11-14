<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc28-1biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-group" /></template>
<style>
.dc28-1biy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.848 5.848Q2.75 6.947 2.75 8.5q0 3.75 3.75 3.75t3.75-3.75T6.5 4.75q-1.553 0-2.652 1.098M13.75 8.5q0-3.75 3.75-3.75t3.75 3.75t-3.75 3.75t-3.75-3.75M3.085 15.607Q1.75 17.175 1.75 19.5q0 1.75 1.75 1.75h6q1.75 0 1.75-1.75q0-2.325-1.335-3.893Q8.545 14 6.5 14t-3.415 1.607M12.75 19.5q0-2.325 1.335-3.893Q15.455 14 17.5 14t3.415 1.607q1.335 1.568 1.335 3.893q0 1.75-1.75 1.75h-6q-1.75 0-1.75-1.75");
}

</style>
