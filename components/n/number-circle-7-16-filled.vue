<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a7n17cbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-7-16-filled" /></template>
<style>
.a7n17cbcx {
  fill: currentColor;
  d: path("M1 8a7 7 0 1 1 14 0A7 7 0 0 1 1 8m5-3a.5.5 0 0 0 0 1h3.005a13 13 0 0 0-.474.763c-.574.998-1.225 2.429-1.524 4.152a.5.5 0 1 0 .986.17c.273-1.577.871-2.896 1.405-3.823c.266-.463.514-.825.694-1.07a8 8 0 0 1 .268-.344l.014-.016l.002-.002A.5.5 0 0 0 10 5z");
}

</style>
