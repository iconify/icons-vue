<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zndlcdjau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tablet-android-outline-sharp" /></template>
<style>
.zndlcdjau {
  fill: currentColor;
  d: path("M3 23V1h18v22zm2-5v3h14v-3zm5 2h4v-1h-4zm-5-4h14V6H5zM5 4h14V3H5zm0 0V3zm0 14v3z");
}

</style>
