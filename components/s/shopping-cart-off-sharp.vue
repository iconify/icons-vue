<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epqx1gb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shopping-cart-off-sharp" /></template>
<style>
.epqx1gb4d {
  fill: currentColor;
  d: path("M14.921 12.116L7.306 4.5h12.971l-4.129 7.616zm-7.613 9q-.614 0-1.057-.434t-.443-1.066t.443-1.067q.443-.433 1.057-.433t1.056.433q.444.434.444 1.067q0 .632-.443 1.066t-1.057.434m13 .607l-5.62-5.607H4.925l2.629-4.82L5.484 6.9L2.24 3.654l.707-.708l18.07 18.07zm-4.673-1.041q-.443-.434-.443-1.066t.443-1.067q.444-.433 1.057-.433t1.057.433q.443.434.443 1.067q0 .632-.443 1.066t-1.057.434t-1.057-.434");
}

</style>
