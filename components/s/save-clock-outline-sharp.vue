<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj3e7i4pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:save-clock-outline-sharp" /></template>
<style>
.qj3e7i4pq {
  fill: currentColor;
  d: path("M5 19V5v5.652v-.036zm-1 1V4h12.577L20 7.423v3.444q-.244-.09-.494-.134T19 10.652V7.85L16.15 5H5v14h7.32q.078.28.2.521q.122.24.255.479zm11.549-.164Q14.385 18.67 14.385 17t1.164-2.835T18.384 13q1.672 0 2.836 1.165q1.165 1.164 1.165 2.835t-1.165 2.836T18.385 21t-2.836-1.164m3.22-2.997v-2.723H18v3.046l2.04 2.04l.547-.546zm-12-7.07h7.423v-3H6.77zm5.262 6.754q-.006-.052-.009-.101t-.003-.1q.077-.87.395-1.687q.317-.818.863-1.504q-.244-.287-.597-.44t-.738-.153q-.808 0-1.375.577T10 14.5q0 .821.601 1.368t1.43.655");
}

</style>
