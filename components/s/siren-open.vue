<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz7xc-pkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:siren-open" /></template>
<style>
.oz7xc-pkk {
  fill: currentColor;
  d: path("M4 21q-.825 0-1.412-.587T2 19v-2q0-.825.588-1.412T4 15h1v-5q0-2.925 2.038-4.962T12 3t4.963 2.038T19 10v1.075q-.25-.05-.488-.062T18 11q-2.9 0-4.95 2.038T11 18q0 .775.163 1.538T11.675 21zm4-8h2v-3q0-.825.588-1.412T12 8V6q-1.65 0-2.825 1.175T8 10zm6.463 8.538Q13 20.075 13 18t1.463-3.537T18 13t3.538 1.463T23 18t-1.463 3.538T18 23t-3.537-1.463M16.2 20.5l2.8-2.8V20h1v-4h-4v1h2.3l-2.8 2.8z");
}

</style>
