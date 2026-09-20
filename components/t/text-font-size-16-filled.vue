<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lcxv_kblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-font-size-16-filled" /></template>
<style>
.lcxv_kblk {
  fill: currentColor;
  d: path("M10.5 1.75a.75.75 0 0 1 .705.494l4 11a.75.75 0 0 1-1.41.512L12.61 10.5H8.39l-1.184 3.256a.75.75 0 0 1-1.397.032L5.27 12.5H2.729l-.537 1.288a.75.75 0 0 1-1.384-.576l2.5-6l.05-.1a.75.75 0 0 1 1.334.1l1.76 4.224l3.343-9.192a.75.75 0 0 1 .705-.494M3.354 11h1.292L4 9.45zm5.58-2h3.131L10.5 4.694z");
}

</style>
