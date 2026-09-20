<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7rmc0bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scanner-outline" /></template>
<style>
.k7rmc0bbs {
  fill: currentColor;
  d: path("M17.985 13L4.846 8.246l.316-.938L18.608 12.2q.73.277 1.061.854T20 14.269v3.115q0 .691-.462 1.153T18.384 19H5.616q-.691 0-1.153-.462T4 17.384v-2.768q0-.691.463-1.153T5.616 13zm.4 5q.23 0 .423-.192t.192-.424v-2.768q0-.231-.192-.424T18.384 14H5.616q-.231 0-.424.192T5 14.616v2.769q0 .23.192.423t.423.192zm-8.231-1.5H17.5v-1h-7.346zm-2.605.049q.22-.22.22-.549t-.22-.549t-.549-.22t-.549.22t-.22.549t.22.549t.549.22t.549-.22M5 18v-4z");
}

</style>
