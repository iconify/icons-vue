<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfrh5_bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-warning-amber" /></template>
<style>
.lfrh5_bfw {
  fill: currentColor;
  d: path("M1 21h22L12 2zm3.47-2L12 5.99L19.53 19zM11 16h2v2h-2zm0-6h2v4h-2z");
}

</style>
