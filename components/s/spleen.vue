<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvrkg1tpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:spleen" /></template>
<style>
.lvrkg1tpu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.97 17.53q-1.645-1.644-.655-4.845q.921-2.982 3.655-5.715q2.759-2.76 5.691-3.773q3.231-1.116 4.869.523q1.655 1.654.675 4.349q-.901 2.476-3.521 4.293q-1.747 1.272-3.863 3.889Q8.81 17.5 8.28 18.03q-1.345 1.346-2.789 1.083q-1.147-.209-2.521-1.583m12.53-2.28q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768T18 17.75q-2.5 0-2.5-2.5m1.5 0q0 1 1 1q.414 0 .707-.293T19 15.25t-.293-.707T18 14.25q-1 0-1 1M18 18q-4.25 0-4.25 3.25q0 1.25 1.25 1.25h6q1.25 0 1.25-1.25Q22.25 18 18 18m2.735 3h-5.47q.189-1.5 2.735-1.5t2.735 1.5");
}

</style>
