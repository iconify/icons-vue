<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5q9bhbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:replay-rounded" /></template>
<style>
.m5q9bhbdt {
  fill: currentColor;
  d: path("M8.882 20.374q-1.455-.626-2.542-1.713t-1.714-2.543T4 13q0-.213.143-.357T4.5 12.5t.357.143T5 13q0 2.925 2.038 4.963T12 20t4.963-2.037T19 13t-2.037-4.962T12 6h-.38l1.272 1.273q.146.146.153.344t-.153.364q-.165.165-.357.168q-.19.003-.356-.162l-1.921-1.94q-.243-.243-.243-.566t.243-.566l1.96-1.94q.145-.146.347-.153q.2-.007.366.159q.16.165.162.354t-.162.354L11.619 5H12q1.664 0 3.118.626T17.66 7.34t1.714 2.542T20 13t-.626 3.118t-1.714 2.543t-2.542 1.713T12 21t-3.118-.626");
}

</style>
