<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="txdr_4nbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:spray-can-16-filled" /></template>
<style>
.txdr_4nbu {
  fill: currentColor;
  d: path("M14 1.5a.5.5 0 1 1 1 0a.5.5 0 0 1-1 0m-2 1a.5.5 0 1 1 1 0a.5.5 0 0 1-1 0M10.5 4a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m2 0a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m2-1a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1M14 5.5a.5.5 0 1 1 1 0a.5.5 0 0 1-1 0m-3.012.936a.5.5 0 0 0-.134-.29L9 4.292V2.5a.5.5 0 0 0-.5-.5H6.501a.5.5 0 0 0-.5.5v1.793L4.147 6.146a.5.5 0 0 0-.134.29l-.004.017l-.002.009A.1.1 0 0 0 4 6.5v6.75c0 .966.784 1.75 1.75 1.75h3.5A1.75 1.75 0 0 0 11 13.25V6.5q-.001-.017-.005-.031l-.002-.007zM7.001 3h1v1h-1zm-.293 2h1.586l1 1H5.708z");
}

</style>
