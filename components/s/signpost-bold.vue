<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l1h_lb4kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:signpost-bold" /></template>
<style>
.l1h_lb4kq {
  fill: currentColor;
  d: path("M248.92 104L215.3 66.62A20 20 0 0 0 200.44 60H140V32a12 12 0 0 0-24 0v28H40a20 20 0 0 0-20 20v64a20 20 0 0 0 20 20h76v60a12 12 0 0 0 24 0v-60h60.44a20 20 0 0 0 14.86-6.62L248.92 120a12 12 0 0 0 0-16m-50.26 36H44V84h154.66l25.2 28Z");
}

</style>
