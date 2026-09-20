<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ter3mfbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-cam-stand" /></template>
<style>
.ter3mfbik {
  fill: currentColor;
  d: path("M6 20q-.433 0-.725-.335q-.292-.336-.275-.788l.6-7q.144-1.839 1.223-3.266T9.5 6.534V10q0 1.035.733 1.767T12 12.5q1.04 0 1.77-.733T14.5 10V6.535q1.617.65 2.687 2.077t1.232 3.265l.6 7.1q.018.433-.284.728T18 20zm4.934-8.934Q10.5 10.633 10.5 10V6q0-.633.434-1.066Q11.367 4.5 12 4.5t1.066.434T13.5 6v4q0 .633-.434 1.066q-.433.434-1.066.434t-1.066-.434");
}

</style>
