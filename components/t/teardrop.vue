<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3awyrelh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:teardrop" /></template>
<style>
.b3awyrelh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.25 3.5V12q0 3.831-2.709 6.541Q15.831 21.25 12 21.25t-6.541-2.709Q2.75 15.831 2.75 12t2.709-6.541Q8.169 2.75 12 2.75h8.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
