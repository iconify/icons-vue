<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mc77macjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:push-pin-simple-slash-bold" /></template>
<style>
.mc77macjy {
  fill: currentColor;
  d: path("m216.88 207.93l-160-176a12 12 0 1 0-17.76 16.14L62 73.19L45.93 164H40a12 12 0 0 0 0 24h76v52a12 12 0 0 0 24 0v-52h26.33l32.79 36.07a12 12 0 0 0 17.76-16.14M70.3 164l12.07-68.36L144.51 164ZM90.06 40a12 12 0 0 1 12-12H192a12 12 0 0 1 0 24h-1.7l15.33 86.84a12 12 0 0 1-9.73 13.91a12.6 12.6 0 0 1-2.1.18A12 12 0 0 1 182 143l-16.07-91h-63.87a12 12 0 0 1-12-12");
}

</style>
