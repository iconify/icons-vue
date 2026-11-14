<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5ryebbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:progress-circle-100" /></template>
<style>
.f5ryebbqx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m1.061 13.435Q3.25 15.624 3.25 12t2.563-6.187T12 3.25t6.187 2.563T20.75 12t-2.563 6.187T12 20.75t-6.187-2.563m1.414-10.96Q9.204 5.25 12 5.25t4.773 1.977T18.75 12t-1.977 4.773T12 18.75t-4.773-1.977T5.25 12t1.977-4.773");
}

</style>
