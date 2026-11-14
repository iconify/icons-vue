<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epnqwacpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nose-clip" /></template>
<style>
.epnqwacpk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.482 14.811q-1.843-2.776-1.317-6.267Q6.887 3.75 12 3.75t5.835 4.794q.526 3.491-1.317 6.267q1.232.732 1.232 3.189q0 3.5-2.5 3.5t-2.5-3.5q0-3.228 2.127-3.479q1.965-2.502 1.475-5.753Q15.822 5.25 12 5.25T7.648 8.768q-.49 3.251 1.475 5.753q2.127.251 2.127 3.479q0 3.5-2.5 3.5T6.25 18q0-2.457 1.232-3.189");
}

</style>
