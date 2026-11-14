<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln5xbnexj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sandbag-bin" /></template>
<style>
.ln5xbnexj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.25 2.75h3.5q3 0 3 3q0 .879-.257 1.5h1.257q1.243 0 2.121.879q.879.878.879 2.121q0 .831-.393 1.5H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .092-.022.182l-2 8q-.015.06-.04.117t-.059.11t-.076.098t-.091.084t-.104.068t-.114.05t-.12.031q-.062.01-.124.01h-15q-.062 0-.124-.01q-.061-.011-.12-.031t-.114-.05t-.104-.068t-.091-.084t-.076-.098t-.059-.11q-.024-.057-.04-.117l-2-8q-.018-.072-.021-.146q-.004-.073.007-.146t.036-.143t.063-.133t.088-.118q.049-.055.109-.099q.059-.044.126-.075q.066-.032.138-.05q.09-.022.182-.022h1.143q-.393-.669-.393-1.5q0-3 3-3h1.257q-.257-.621-.257-1.5q0-3 3-3");
}

</style>
