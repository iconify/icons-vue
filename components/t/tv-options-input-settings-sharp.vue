<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyhucab9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-options-input-settings-sharp" /></template>
<style>
.tyhucab9q {
  fill: currentColor;
  d: path("M11.5 15.885h1l.108-.885q.473-.106.889-.32t.75-.588l.853.354l.539-.834l-.708-.616q.146-.498.146-.996t-.146-.996l.708-.615l-.539-.835l-.854.354q-.332-.374-.749-.588q-.416-.214-.89-.32l-.107-.884h-1L11.392 9q-.473.106-.889.32t-.75.588L8.9 9.554l-.538.834l.707.616q-.146.498-.146.996t.146.996l-.708.615l.539.835l.854-.354q.333.374.749.588t.89.32zm-1.028-2.357q-.626-.626-.626-1.528t.626-1.528T12 9.846t1.528.626t.626 1.528t-.626 1.528t-1.528.626t-1.528-.626M3 19V5h18v14z");
}

</style>
