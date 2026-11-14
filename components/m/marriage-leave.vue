<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy8llxdda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:marriage-leave" /></template>
<style>
.qy8llxdda {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.28 3.26l.164.295q.692 1.245-.136 2.402l-.075.105q-.453.634-1.234.634t-1.235-.636l-.073-.101q-.829-1.159-.138-2.403l.166-.297q.418-.753 1.28-.753q.861 0 1.28.753m-1.282 5.17Q10.494 7.25 8.5 7.25q-2.382 0-4.066 1.684T2.75 13t1.684 4.066T8.5 18.75q1.994 0 3.498-1.18q1.506 1.182 3.502 1.182q2.383 0 4.067-1.685T21.25 13q.001-2.382-1.683-4.067T15.5 7.248q-1.996 0-3.502 1.182");
}

</style>
