<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr5hmpbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-camera-outline-sharp" /></template>
<style>
.lr5hmpbgj {
  fill: currentColor;
  d: path("M3 20V6h4.573l1.85-2h5.154l1.85 2H21v14zm1-1h16V7h-4.011l-1.845-2H9.856L8.012 7H4zm5.692-2.654l.708-.707l-2.088-2.089h7.377L13.6 15.639l.708.707l3.308-3.307l-3.308-3.308l-.708.708l2.1 2.111H8.3l2.1-2.111l-.708-.708l-3.308 3.308z");
}

</style>
