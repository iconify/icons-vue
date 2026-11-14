<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik2xy-59u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mri-scan-image" /></template>
<style>
.ik2xy-59u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h9.25q2.123 0 3.624 1.501t1.501 3.624v9.25q0 2.123-1.501 3.624t-3.624 1.501h-9.25q-2.123 0-3.624-1.501T2.25 16.625v-9.25q0-2.123 1.501-3.624T7.375 2.25m.154 4.503Q5.75 8.937 5.75 12t1.779 5.247Q9.365 19.5 12 19.5t4.471-2.253Q18.25 15.063 18.25 12t-1.779-5.247Q14.635 4.5 12 4.5T7.529 6.753");
}

</style>
