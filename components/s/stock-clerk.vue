<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw-j6db7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stock-clerk" /></template>
<style>
.lw-j6db7i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.464 3.714Q7 5.179 7 7.25t1.464 3.536T12 12.25t3.536-1.464Q17 9.321 17 7.25t-1.464-3.536Q14.071 2.25 12 2.25T8.464 3.714m3.923 11.79q.224-.913.818-1.456Q12.62 14 12 14q-3.924 0-6.483 1.933Q2.75 18.022 2.75 21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-6 7.75-6q.196 0 .387.004M15.75 14.5h4.5q2.25 0 2.25 2.25v3.5q0 2.25-2.25 2.25h-4.5q-2.25 0-2.25-2.25v-3.5q0-2.25 2.25-2.25m1.5 1.5v.75H15q0-.75.75-.75zm3 0h-1.5v.75H21q0-.75-.75-.75m.75 2.25h-6v2q0 .75.75.75h4.5q.75 0 .75-.75zm-1.511 1.25q.036.123.067.25h.194v-.25z");
}

</style>
