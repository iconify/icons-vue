<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_yr7pthw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:manicure" /></template>
<style>
.d_yr7pthw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 1.75h-1.5q-2.5 0-2.5 2.5v4q0 .564.127 1.002q-1.681.042-2.882 1.243Q2.75 11.74 2.75 13.5V18q0 1.76 1.245 3.005T7 22.25h6q1.76 0 3.005-1.245T17.25 18v-4.5q0-1.76-1.245-3.005q-1.227-1.227-2.955-1.245q.2-.458.2-1v-4q0-1.036-.732-1.768T10.75 1.75m8.336 1.281Q21.25 5.737 21.25 7.25q0 2.75-2.75 2.75t-2.75-2.75q0-1.513 2.164-4.219q.094-.116.224-.188q.131-.072.279-.088q.148-.017.292.025q.143.041.26.134q.065.052.117.117");
}

</style>
