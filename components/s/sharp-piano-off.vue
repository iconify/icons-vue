<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sigej-b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-piano-off" /></template>
<style>
.sigej-b1c {
  fill: currentColor;
  d: path("M21.19 21.19L2.81 2.81L1.39 4.22L3 5.83V21h15.17l1.61 1.61zM8.25 19H5V7.83l2 2v4.67h1.25zm1.5 0v-4.5H11v-.67l3.25 3.25V19zM5.83 3H21v15.17l-2-2V5h-2v9.17l-4-4V5h-2v3.17z");
}

</style>
