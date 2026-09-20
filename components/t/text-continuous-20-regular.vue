<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n-2bnugxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-continuous-20-regular" /></template>
<style>
.n-2bnugxq {
  fill: currentColor;
  d: path("M2 5.5a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1-.5-.5m0 9a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1-.5-.5m1.354-6.354a.5.5 0 1 0-.708.708L3.793 10l-1.147 1.146a.5.5 0 0 0 .708.708l1.5-1.5a.5.5 0 0 0 0-.708zM7.5 8h10a.5.5 0 0 1 0 1h-10a.5.5 0 0 1 0-1m0 3a.5.5 0 0 0 0 1h10a.5.5 0 0 0 0-1z");
}

</style>
