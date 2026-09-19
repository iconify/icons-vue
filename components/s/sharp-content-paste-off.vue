<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpjwlormo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-content-paste-off" /></template>
<style>
.cpjwlormo {
  fill: currentColor;
  d: path("M21.19 21.19L2.81 2.81L1.39 4.22L3 5.83V21h15.17l1.61 1.61zM5 19V7.83L16.17 19zM17 8V5h2v11.17l2 2V3h-6.18C14.4 1.84 13.3 1 12 1s-2.4.84-2.82 2H5.83l5 5zm-5-5c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1");
}

</style>
