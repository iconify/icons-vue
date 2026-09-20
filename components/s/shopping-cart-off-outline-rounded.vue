<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9jry5bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shopping-cart-off-outline-rounded" /></template>
<style>
.p9jry5bjd {
  fill: currentColor;
  d: path("M15.306 12.116h-.385l-1-1h1.629l2.75-5.077q.116-.212.01-.375q-.106-.164-.318-.164H8.306l-1-1h11.106q.652 0 .964.536q.313.535-.026 1.168l-2.78 5.13q-.218.405-.502.593t-.762.189m-7.998 9q-.633 0-1.067-.434t-.433-1.067t.433-1.066t1.067-.434t1.066.434q.434.434.434 1.066t-.434 1.067t-1.066.433m12.646.254l-5.266-5.253H7.446q-.869 0-1.3-.726t-.027-1.482l1.435-2.612L5.484 6.9L2.593 4.008q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16l17.362 17.362q.14.14.153.341q.012.2-.153.366q-.16.16-.354.16t-.354-.16m-6.266-6.253l-3-3H8.215l-1.192 2.23q-.154.289-.01.529t.433.24zm1.862-4h-1.629zm.085 9.566q-.443-.434-.443-1.066t.443-1.067q.444-.433 1.057-.433t1.057.433q.443.434.443 1.067q0 .632-.443 1.066t-1.057.434t-1.057-.434");
}

</style>
