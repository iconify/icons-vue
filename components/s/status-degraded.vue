<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz3b-z1jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:status-degraded" /></template>
<style>
.pz3b-z1jw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 2.75q2.25 0 2.25 2.25v14q0 2.25-2.25 2.25T17.75 19V5q0-2.25 2.25-2.25M17 9q0-2.25-2.25-2.25T12.5 9v10q0 2.25 2.25 2.25T17 19zm-7.5 1.75q2.25 0 2.25 2.25v6q0 2.25-2.25 2.25T7.25 19v-6q0-2.25 2.25-2.25m-3 5.75q0-2.25-2.25-2.25T2 16.5V19q0 2.25 2.25 2.25T6.5 19z");
}

</style>
