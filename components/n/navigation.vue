<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv-ceeele"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:navigation" /></template>
<style>
.rv-ceeele {
  fill: currentColor;
  d: path("m5 21l-1-1l8-18l8 18l-1 1l-7-3z");
}

</style>
