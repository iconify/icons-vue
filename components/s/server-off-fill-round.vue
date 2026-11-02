<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvlgjsbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-fill-round" /></template>
<style>
.pvlgjsbrh {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-1.941-1.941A4 4 0 0 1 18 21H6a4 4 0 0 1 0-8h5.586l-2-2H6a4 4 0 0 1-3.028-6.614L1.293 2.707a.999.999 0 1 1 1.414-1.414M15.243 11l-8-8H18a4 4 0 0 1 0 8Zm6.697 6.697L17.243 13H18a4 4 0 0 1 3.94 4.697M7.01 16H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
