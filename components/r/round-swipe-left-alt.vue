<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg9d83b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-swipe-left-alt" /></template>
<style>
.gg9d83b2t {
  fill: currentColor;
  d: path("M10.1 13a5 5 0 1 0 0-2H5.83l.88-.88A.996.996 0 1 0 5.3 8.71L2.71 11.3a.996.996 0 0 0 0 1.41L5.3 15.3a.996.996 0 1 0 1.41-1.41L5.83 13z");
}

</style>
