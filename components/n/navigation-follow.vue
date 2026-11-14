<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_r0o-bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:navigation-follow" /></template>
<style>
.u_r0o-bhf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m9.351 5.161l1.758 4.616q.396 1.036-.461 1.741q-.857.704-1.798.116l-1.204-.753q-.398-.248-.796 0l-1.205.753q-.94.588-1.797-.116q-.857-.705-.461-1.742l1.758-4.615q.552-1.45 2.103-1.45t2.103 1.45");
}

</style>
