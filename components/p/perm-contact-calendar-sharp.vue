<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt0pxh3rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:perm-contact-calendar-sharp" /></template>
<style>
.zt0pxh3rc {
  fill: currentColor;
  d: path("M5 18.85q1.35-1.325 3.138-2.087T12 16t3.863.763T19 18.85V6H5zm4.525-5.875Q8.5 11.95 8.5 10.5t1.025-2.475T12 7t2.475 1.025T15.5 10.5t-1.025 2.475T12 14t-2.475-1.025M3 22V4h3V2h2v2h8V2h2v2h3v18z");
}

</style>
