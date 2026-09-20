<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntkuibzus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pan-zoom-rounded" /></template>
<style>
.ntkuibzus {
  fill: currentColor;
  d: path("M5.708 19H8.5q.214 0 .357.143T9 19.5t-.143.357T8.5 20H4.808q-.348 0-.578-.23T4 19.192V15.5q0-.213.143-.357T4.5 15t.357.143T5 15.5v2.792l3.246-3.246q.14-.14.344-.15t.364.15t.16.354t-.16.354zM19 5.708l-3.246 3.246q-.14.14-.344.15t-.364-.15t-.16-.354t.16-.354L18.292 5H15.5q-.213 0-.357-.143T15 4.5t.143-.357T15.5 4h3.692q.349 0 .578.23t.23.578V8.5q0 .214-.143.357T19.5 9t-.357-.143T19 8.5z");
}

</style>
