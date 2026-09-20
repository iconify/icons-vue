<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjh5p5b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shopping-cart-off" /></template>
<style>
.hjh5p5b0q {
  fill: currentColor;
  d: path("M15.306 12.116h-.385L7.306 4.5h11.106q.652 0 .964.536q.313.535-.026 1.168l-2.78 5.13q-.218.405-.502.593t-.762.189m-7.998 9q-.614 0-1.057-.434t-.443-1.067t.443-1.066t1.057-.434t1.056.434q.444.434.444 1.066t-.443 1.067t-1.057.433m13 .608l-5.62-5.608H7.446q-.869 0-1.3-.726t-.027-1.481l1.435-2.612L5.484 6.9L2.24 3.654l.707-.708l18.07 18.07zm-6.62-6.608l-3-3H8.215l-1.192 2.231q-.154.288-.01.529t.433.24zm1.947 5.567q-.443-.434-.443-1.067q0-.632.443-1.066q.444-.434 1.057-.434t1.057.434t.443 1.066t-.443 1.067t-1.057.433t-1.057-.433");
}

</style>
