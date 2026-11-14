<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuum5gblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:video-lock" /></template>
<style>
.wuum5gblh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.125 5.25h-4.25q-2.123 0-3.624 1.501T1.75 10.375v3.25q0 2.123 1.501 3.624t3.624 1.501h4.25q2.123 0 3.624-1.501q1.09-1.091 1.389-2.509l2.352 1.373q1.25.729 2.505.008t1.255-2.168v-3.906q0-1.447-1.255-2.168t-2.505.008L16.138 9.26q-.299-1.418-1.389-2.509q-1.501-1.501-3.624-1.501m-2.875 5.5v-.25q0-.75.75-.75t.75.75v.25zm3 .338q1 .581 1 2.162v.5q0 1.036-.732 1.768t-1.768.732h-1.5q-1.036 0-1.768-.732T5.75 13.75v-.5q0-1.581 1-2.162V10.5q0-2.25 2.25-2.25t2.25 2.25z");
}

</style>
