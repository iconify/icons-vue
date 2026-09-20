<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7p2qflns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-search-rounded" /></template>
<style>
.r7p2qflns {
  fill: currentColor;
  d: path("M8.27 10.85v-2.7q0-.242.204-.36t.417.012l2.165 1.35q.192.13.192.348t-.192.348l-2.165 1.35q-.212.13-.417.013t-.205-.361m1.27 4.38q-2.399 0-4.065-1.666T3.808 9.5t1.666-4.065T9.538 3.77t4.065 1.666T15.269 9.5q0 1.042-.369 2.017t-.97 1.668l5.909 5.907q.14.14.15.345q.009.203-.15.363q-.16.16-.354.16t-.354-.16l-5.908-5.908q-.75.639-1.725.989t-1.96.35m0-1q1.99 0 3.361-1.37q1.37-1.37 1.37-3.361T12.9 6.14T9.54 4.77q-1.991 0-3.361 1.37T4.808 9.5t1.37 3.36t3.36 1.37");
}

</style>
