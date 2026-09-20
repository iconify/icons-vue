<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mif-89bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-multiple-24-filled" /></template>
<style>
.mif-89bms {
  fill: currentColor;
  d: path("M7.75 5A3.25 3.25 0 0 0 4.5 8.25v5.5A3.25 3.25 0 0 0 7.75 17h5A3.25 3.25 0 0 0 16 13.75v-5.5A3.25 3.25 0 0 0 12.75 5zM3.507 8.007q-.007.12-.007.243v5.5A4.25 4.25 0 0 0 7.75 18h5q.123 0 .244-.007A3.25 3.25 0 0 1 10.25 19.5h-2.5A5.75 5.75 0 0 1 2 13.75v-3c0-1.153.6-2.166 1.507-2.743m18.495-.254c0-1.416-1.594-2.246-2.754-1.434L17 7.893v6.214l2.248 1.574c1.16.812 2.754-.018 2.754-1.434z");
}

</style>
