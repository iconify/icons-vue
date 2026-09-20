<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miv0rd35g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-sharp" /></template>
<style>
.miv0rd35g {
  fill: currentColor;
  d: path("M2 20V4h20v16zm9-7h8V7h-8z");
}

</style>
