<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vplb_zb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:postman-collection" /></template>
<style>
.vplb_zb9l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.25 10.438q1.5.531 1.5 2.562v6.5q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75V11q0-2.75 2.75-2.75h3.5q.149 0 .287.057t.243.163l1.72 1.719V7.5q0-2.121 2-2.243V4.5q0-.932.659-1.591T15 2.25h3q2.25 0 2.25 2.25zm-1.5-.188V4.5q0-.75-.75-.75h-3q-.75 0-.75.75v.75H15q2.25 0 2.25 2.25v2.75zm-5.25-3.5H13q-.75 0-.75.75v2.75h3.5V7.5q0-.75-.75-.75z");
}

</style>
