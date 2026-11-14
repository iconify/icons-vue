<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7n-7ubjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mango-tree" /></template>
<style>
.c7n-7ubjm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 8.5q-.001 2.834 2.727 4.8Q5 13.984 5 15.25Q5 18 7.25 18t2.25-2.75q0-.118-.004-.231q.843.166 1.754.214V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6.267q.911-.048 1.754-.214q-.004.113-.004.231q0 2.75 2.25 2.75T19 15.25q0-1.266-.477-1.95q2.728-1.966 2.727-4.8q.001-2.874-2.806-4.857Q15.76 1.748 12 1.748T5.556 3.643Q2.749 5.625 2.75 8.5");
}

</style>
