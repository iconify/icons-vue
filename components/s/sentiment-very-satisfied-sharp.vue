<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m97jbs-2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sentiment-very-satisfied-sharp" /></template>
<style>
.m97jbs-2o {
  fill: currentColor;
  d: path("M14.636 16.095q1.205-.79 1.81-2.095H7.554q.605 1.306 1.81 2.095t2.636.79t2.636-.79M7.8 10.577l1.1-1.088l1.089 1.088l.627-.627L8.9 8.223L7.173 9.95zm6.212 0L15.1 9.489l1.1 1.088l.627-.627L15.1 8.223L13.385 9.95zm-5.519 9.715q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709t-3.51-.708");
}

</style>
