<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgqf4mmsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:roundabout-left-outline-sharp" /></template>
<style>
.xgqf4mmsw {
  fill: currentColor;
  d: path("M15 21v-8.05h1q1.65 0 2.825-1.15T20 9t-1.175-2.825T16 5t-2.8 1.175T12.05 9v1H5.825l1.6 1.6L6 13L2 9l4-4l1.4 1.4L5.825 8h4.325q.35-2.125 1.988-3.562T16 3q2.5 0 4.25 1.75T22 9q0 2.225-1.437 3.863T17 14.85V21z");
}

</style>
