<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhwe1475x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shopping-cart-off-rounded" /></template>
<style>
.qhwe1475x {
  fill: currentColor;
  d: path("M15.306 12.116h-.385L7.306 4.5h11.106q.652 0 .964.536q.313.535-.026 1.168l-2.78 5.13q-.218.405-.502.593t-.762.189m-7.998 9q-.614 0-1.057-.434t-.443-1.067t.443-1.066t1.057-.434t1.056.434q.444.434.444 1.066t-.443 1.067t-1.057.433m12.646.254l-5.266-5.253H7.446q-.869 0-1.3-.726t-.027-1.482l1.435-2.612L5.484 6.9L2.593 4.008q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16l17.362 17.362q.14.14.153.341q.012.2-.153.366q-.16.16-.354.16t-.354-.16m-4.318-.687q-.444-.434-.444-1.066t.444-1.067q.443-.433 1.056-.433t1.057.433t.443 1.067t-.443 1.066t-1.057.434t-1.056-.434");
}

</style>
