<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="f_p5jjbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:prohibited" /></template>
<style>
.f_p5jjbvc {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M18 0C8.059 0 0 8.059 0 18s8.059 18 18 18s18-8.059 18-18S27.941 0 18 0m13 18c0 2.565-.753 4.95-2.035 6.965L11.036 7.036A12.9 12.9 0 0 1 18 5c7.18 0 13 5.821 13 13M5 18c0-2.565.753-4.95 2.036-6.964l17.929 17.929A12.93 12.93 0 0 1 18 31c-7.179 0-13-5.82-13-13");
}

</style>
