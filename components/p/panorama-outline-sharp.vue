<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak13kd81v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:panorama-outline-sharp" /></template>
<style>
.ak13kd81v {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm2-2h12l-3.75-5l-3 4L9 12zm-2 2V6z");
}

</style>
