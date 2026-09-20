<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcrupb-zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wrap-text-rounded" /></template>
<style>
.jcrupb-zf {
  fill: currentColor;
  d: path("M5.5 12.25q-.213 0-.356-.144T5 11.749t.144-.356t.356-.143h11.423q1.293 0 2.185.915q.892.914.892 2.2t-.892 2.211t-2.185.924h-3.304l1.3 1.358q.147.165.14.362q-.006.198-.14.346q-.165.165-.366.168q-.201.002-.347-.163l-1.967-2.006q-.112-.13-.165-.27q-.053-.139-.053-.298t.063-.295t.174-.267l1.948-1.987q.146-.165.347-.165t.37.165q.156.166.149.357q-.006.191-.153.357l-1.3 1.338h3.304q.879 0 1.478-.624T19 14.369t-.599-1.5t-1.478-.619zm0 5.25q-.213 0-.356-.144T5 16.999t.144-.356t.356-.143h2.808q.212 0 .356.144t.144.357t-.144.356t-.356.143zM5.5 7q-.213 0-.356-.144T5 6.499t.144-.356T5.5 6h13.058q.212 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
