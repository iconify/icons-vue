<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gmh1acb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-first-line-20-regular" /></template>
<style>
.gmh1acb-q {
  fill: currentColor;
  d: path("M3.354 3.146a.5.5 0 1 0-.708.708L3.793 5L2.646 6.146a.5.5 0 1 0 .708.708l1.5-1.5a.5.5 0 0 0 0-.708zM7.5 4a.5.5 0 0 0 0 1h10a.5.5 0 0 0 0-1zm-5 10a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1zM2 9.5a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1-.5-.5");
}

</style>
