<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsffixb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:total-dissolved-solids" /></template>
<style>
.qsffixb7w {
  fill: currentColor;
  d: path("M5.339 11.8q.605-1.848 2.268-3.949T12 3.308q2.73 2.442 4.393 4.543t2.268 3.949zm13.627 2.4q-.052.494-.201.957t-.39.876l-4.423 4.404q-.413.24-.866.377q-.453.136-.942.163zm-4.383-.4h1.446l-6.677 6.658q-.267-.087-.517-.192q-.249-.104-.48-.264zm-4.764 0h1.446l-4.648 4.648q-.182-.196-.327-.398t-.286-.434zm-4.75 0h1.447L5.13 15.185q-.085-.349-.094-.693t.032-.692");
}

</style>
