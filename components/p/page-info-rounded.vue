<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nflxf3bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:page-info-rounded" /></template>
<style>
.nflxf3bqs {
  fill: currentColor;
  d: path("M15.472 18.201q-.856-.857-.856-2.085q0-1.23.856-2.086q.857-.857 2.086-.857t2.085.857t.857 2.086t-.857 2.085t-2.085.857q-1.23 0-2.086-.857m-3.741-1.586H5.5q-.213 0-.357-.143Q5 16.329 5 16.115q0-.213.143-.356t.357-.143h6.23q.214 0 .358.143t.143.357t-.143.356t-.357.144M4.357 9.97Q3.5 9.113 3.5 7.884T4.357 5.8t2.085-.857q1.23 0 2.086.857q.857.857.857 2.085q0 1.23-.857 2.086q-.857.857-2.086.857T4.357 9.97M18.5 8.385h-6.23q-.214 0-.358-.144t-.143-.356t.143-.357t.357-.143H18.5q.214 0 .357.143t.143.357t-.143.356t-.357.144");
}

</style>
