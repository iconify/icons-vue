<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivlt5pbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:multichannel" /></template>
<style>
.ivlt5pbuw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 2.25Q1.75 2.25 1.75 5T4.5 7.75q.875 0 1.471-.278l2.726 2.385Q8.25 10.705 8.25 12t.447 2.143l-2.726 2.385q-.596-.278-1.471-.278q-2.75 0-2.75 2.75t2.75 2.75T7.25 19q0-.814-.241-1.387l2.722-2.381q.875.518 2.269.518t2.269-.518l2.722 2.381q-.241.573-.241 1.387q0 2.75 2.75 2.75T22.25 19t-2.75-2.75q-.875 0-1.471.278l-2.726-2.385q.447-.848.447-2.143t-.447-2.143l2.726-2.385q.596.278 1.471.278q2.75 0 2.75-2.75T19.5 2.25T16.75 5q0 .814.241 1.387l-2.722 2.381Q13.394 8.25 12 8.25t-2.269.518L7.009 6.387Q7.25 5.814 7.25 5q0-2.75-2.75-2.75");
}

</style>
