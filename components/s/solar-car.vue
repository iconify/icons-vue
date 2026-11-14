<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_31t_d0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:solar-car" /></template>
<style>
.e_31t_d0l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.5 2.75h-7Q6.25 2.75 6.25 5T8.5 7.25h2.75v1.5H9q-.09 0-.177.021t-.166.062t-.148.1q-.067.058-.119.131L6.114 12.25H4q-2.25 0-2.25 2.25V18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.81q.345 2 2.69 2t2.69-2h4.62q.345 2 2.69 2t2.69-2h1.81q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.5q0-2.25-2.25-2.25h-2.114L15.61 9.064q-.052-.073-.119-.131q-.068-.059-.148-.1t-.166-.062T15 8.75h-2.25v-1.5h2.75q2.25 0 2.25-2.25T15.5 2.75m-3.5 7.5h2.614l2.276 3.186q.052.073.119.131q.068.059.148.1t.166.062t.177.021H20q.75 0 .75.75v2.75h-1.06q-.345-2-2.69-2t-2.69 2H9.69q-.345-2-2.69-2t-2.69 2H3.25V14.5q0-.75.75-.75h2.5q.09 0 .177-.021t.166-.062t.148-.1q.067-.058.119-.131l2.276-3.186z");
}

</style>
