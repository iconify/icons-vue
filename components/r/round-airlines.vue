<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt9xzb3hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-airlines" /></template>
<style>
.zt9xzb3hu {
  fill: currentColor;
  d: path("M19.59 4h-5.01c-.99 0-1.91.49-2.47 1.3L2 20h17l2.56-13.63C21.79 5.14 20.84 4 19.59 4M14.5 14a2.5 2.5 0 0 1 0-5a2.5 2.5 0 0 1 0 5");
}

</style>
