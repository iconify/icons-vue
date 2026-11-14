<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7yl-3bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sofa-three-seat" /></template>
<style>
.d7yl-3bva {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22.25 11.5q0-1.837-1.5-2.174V7.5q0-2.25-2.25-2.25h-13q-.932 0-1.591.659T3.25 7.5v1.826q-1.5.337-1.5 2.174V18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146zm-8.5 1.25h-3.5v-6h3.5zm1.5 0v-6h3.25q.75 0 .75.75v1.826q-1.5.337-1.5 2.174v1.25zm-6.5 0h-2.5V11.5q0-1.837-1.5-2.174V7.5q0-.75.75-.75h3.25z");
}

</style>
