<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qerbeabqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:memory-bold" /></template>
<style>
.qerbeabqs {
  fill: currentColor;
  d: path("M232 52H24A20 20 0 0 0 4 72v128a12 12 0 0 0 24 0v-12h20v12a12 12 0 0 0 24 0v-12h20v12a12 12 0 0 0 24 0v-12h24v12a12 12 0 0 0 24 0v-12h20v12a12 12 0 0 0 24 0v-12h20v12a12 12 0 0 0 24 0V72a20 20 0 0 0-20-20M28 76h200v88H28Zm92 64v-40a12 12 0 0 0-12-12H56a12 12 0 0 0-12 12v40a12 12 0 0 0 12 12h52a12 12 0 0 0 12-12m-24-12H68v-16h28Zm52 24h52a12 12 0 0 0 12-12v-40a12 12 0 0 0-12-12h-52a12 12 0 0 0-12 12v40a12 12 0 0 0 12 12m12-40h28v16h-28Z");
}

</style>
