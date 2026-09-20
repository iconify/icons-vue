<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmvnetbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-landscape-sharp" /></template>
<style>
.xmvnetbdq {
  fill: currentColor;
  d: path("M13 16h5V8h-5zm-7 0h5V8H6zm-4 4V4h20v16z");
}

</style>
