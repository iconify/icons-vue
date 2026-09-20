<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxfmxt-zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:space-dashboard-2-rounded" /></template>
<style>
.yxfmxt-zr {
  fill: currentColor;
  d: path("M20 20V4zM5.615 20h6.27q.67 0 1.143-.472q.472-.472.472-1.143V5.615q0-.67-.472-1.143Q12.556 4 11.885 4h-6.27q-.67 0-1.143.472Q4 4.944 4 5.616v12.769q0 .67.472 1.143q.472.472 1.144.472m10.5 0h2.269q.67 0 1.143-.472q.472-.472.472-1.143v-4.27q0-.67-.472-1.143q-.472-.472-1.143-.472h-2.27q-.67 0-1.143.472q-.472.472-.472 1.144v4.269q0 .67.472 1.143q.472.472 1.144.472m0-8.5h2.269q.67 0 1.143-.472q.472-.472.472-1.143v-4.27q0-.67-.472-1.143Q19.056 4 18.385 4h-2.27q-.67 0-1.143.472q-.472.472-.472 1.144v4.269q0 .67.472 1.143q.472.472 1.144.472");
}

</style>
