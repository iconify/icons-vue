<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-z51zb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-cam-stand-sharp" /></template>
<style>
.h-z51zb_m {
  fill: currentColor;
  d: path("m4.896 20l.704-8.123q.144-1.839 1.223-3.266T9.5 6.534V10q0 1.035.733 1.767T12 12.5q1.04 0 1.77-.733T14.5 10V6.535q1.617.65 2.687 2.077t1.232 3.265L19.098 20zm6.038-8.934Q10.5 10.633 10.5 10V6q0-.633.434-1.066Q11.367 4.5 12 4.5t1.066.434T13.5 6v4q0 .633-.434 1.066q-.433.434-1.066.434t-1.066-.434");
}

</style>
