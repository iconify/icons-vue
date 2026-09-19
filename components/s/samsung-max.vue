<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mienpib6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-max" /></template>
<style>
.mienpib6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.024 40h-8.667L12.976 8h9.381zM42.5 40h-8.667l-4.857-21.571h9.381zm-37-14.857L16.976 40H7.643zm23.476-6.714l-2.512 6.714M30.024 40l2.239-6.974M16.976 40l1.556-10.786m-9.078 1.048L12.976 8");
}

</style>
