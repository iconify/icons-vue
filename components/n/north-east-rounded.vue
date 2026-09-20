<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnfmuq0ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:north-east-rounded" /></template>
<style>
.mnfmuq0ma {
  fill: currentColor;
  d: path("M17 7.708L6.062 18.646q-.14.14-.345.15q-.203.01-.363-.15t-.16-.354t.16-.353L16.292 7H9.5q-.213 0-.357-.143T9 6.5t.143-.357T9.5 6h7.692q.349 0 .578.23t.23.578V14.5q0 .214-.143.357T17.5 15t-.357-.143T17 14.5z");
}

</style>
