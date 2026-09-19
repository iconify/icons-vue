<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki1f0pvph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:stop" /></template>
<style>
.ki1f0pvph {
  fill: currentColor;
  d: path("M6 6h12v12H6z");
}

</style>
