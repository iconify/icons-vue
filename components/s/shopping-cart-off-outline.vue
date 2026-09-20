<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3isvl2wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shopping-cart-off-outline" /></template>
<style>
.x3isvl2wb {
  fill: currentColor;
  d: path("M15.312 12.116h-.385l-1.006-1h1.629l2.75-5.077q.116-.212.01-.375q-.106-.164-.318-.164H8.306l-1-1h11.106q.652 0 .964.536q.313.535-.026 1.168l-2.78 5.13q-.218.405-.499.593t-.76.189m-8.003 9q-.633 0-1.067-.434t-.433-1.067t.433-1.066t1.067-.434t1.066.434q.434.434.434 1.066t-.434 1.067t-1.066.433m13 .608l-5.62-5.608H7.446q-.869 0-1.3-.726t-.027-1.481l1.435-2.612L5.484 6.9L2.24 3.654l.707-.708l18.07 18.07zm-6.62-6.608l-3-3H8.215l-1.192 2.231q-.154.288-.01.529t.433.24zm1.862-4h-1.629zm.085 9.567q-.443-.434-.443-1.067q0-.632.443-1.066q.444-.434 1.057-.434t1.057.434t.443 1.066t-.443 1.067t-1.057.433t-1.057-.433");
}

</style>
