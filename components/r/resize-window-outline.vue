<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2d71j6cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:resize-window-outline" /></template>
<style>
.r2d71j6cg {
  fill: currentColor;
  d: path("M19.6 21L3 4.425L4.425 3L21 19.575zM9.575 21L3 14.425L4.425 13L11 19.575z");
}

</style>
