<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz94cqs0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:quota-progress" /></template>
<style>
.bz94cqs0r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.875 6.75H5.125q-1.398 0-2.386.989q-.989.988-.989 2.386v3.75q0 3.375 3.375 3.375h13.75q3.375 0 3.375-3.375v-3.75q0-3.375-3.375-3.375M6.5 9.25H13q2.25 0 2.25 2.25v1q0 .932-.659 1.591T13 14.75H6.5q-.932 0-1.591-.659T4.25 12.5v-1q0-2.25 2.25-2.25");
}

</style>
