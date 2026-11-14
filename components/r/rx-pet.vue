<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwkai3bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rx-pet" /></template>
<style>
.pwkai3bmw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 5.5Q5.75 2 8.5 2t2.75 3.5T8.5 9T5.75 5.5M15.5 2q-2.75 0-2.75 3.5T15.5 9t2.75-3.5T15.5 2M4 8.5q-2.5 0-2.5 3t2.5 3t2.5-3t-2.5-3m13.5 3q0-3 2.5-3t2.5 3t-2.5 3t-2.5-3m-5.5-.25q2.803 0 5.119 2.559q2.131 2.356 2.131 4.691q0 1.89-1.521 2.615q-1.241.59-2.935.106q-2.794-.798-5.588 0q-1.694.484-2.935-.106Q4.75 20.39 4.75 18.5q0-2.335 2.131-4.691Q9.197 11.25 12 11.25");
}

</style>
