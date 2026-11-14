<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzq7zj5wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:music-store" /></template>
<style>
.yzq7zj5wn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.311 6.205l19.439.274v.022q-.002 2.997-3 2.997q-1.499 0-2.249-.749q-.75.751-2.251.751T12 8.75q-.75.75-2.25.75t-2.251-.751q-.75.75-2.249.75q-2.999 0-3-2.999q0-.154.061-.295m8.346 4.551q-.067.008-.132.029q-.065.02-.125.052t-.114.074t-.098.093t-.08.109t-.059.122t-.037.13T10 11.5v4.392q-.668-.393-1.5-.393q-1.243 0-2.122.879T5.5 18.5t.878 2.122q.879.879 2.122.879t2.122-.879t.878-2.122v-6.338l6.5-.812v3.042q-.668-.394-1.5-.394q-1.243 0-2.122.88q-.878.879-.878 2.121v.002q0 1.242.878 2.121q.879.88 2.122.88t2.122-.88T19.5 17v-6.509q-.001-.042-.006-.084q-.018-.148-.092-.278q-.074-.129-.192-.221q-.098-.077-.217-.117q-.118-.041-.243-.041h-.003q-.045 0-.09.006h-.001z");
}

</style>
