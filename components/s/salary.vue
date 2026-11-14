<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjzlq2bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:salary" /></template>
<style>
.cjzlq2bmw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 5.25H6q-1.76 0-3.005 1.245T1.75 9.5v5q0 1.76 1.245 3.005T6 18.75h12q1.76 0 3.005-1.245T22.25 14.5v-5q0-1.76-1.245-3.005T18 5.25M8.5 12q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5T8.5 12");
}

</style>
