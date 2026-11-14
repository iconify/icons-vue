<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5gc2mbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooth-inlay" /></template>
<style>
.o5gc2mbpu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.279 2.804Q8.894 2.25 8 2.25Q3.25 2.25 3.25 8q0 2.604 1.961 6.176q.381.694.574 1.071l.98 4.9q.308 1.541 1.735 1.541t1.735-1.541l.994-4.47q.054-.177.771-.177t.771.177l.997 4.486q.305 1.525 1.732 1.525t1.735-1.541l.98-4.9q.193-.377.574-1.071Q20.75 10.604 20.75 8q0-5.75-4.75-5.75q-.894 0-2.279.554q-1.115.446-1.721.446t-1.721-.446M9.25 8.5q0-2.25 2.25-2.25h1q.932 0 1.591.659T14.75 8.5V9q0 .932-.659 1.591t-1.591.659h-1q-2.25 0-2.25-2.25z");
}

</style>
