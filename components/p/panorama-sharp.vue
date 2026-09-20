<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bry-7ebgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:panorama-sharp" /></template>
<style>
.bry-7ebgg {
  fill: currentColor;
  d: path("M2 20V4h20v16zm4-4h12l-3.75-5l-3 4L9 12z");
}

</style>
