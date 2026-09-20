<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk4x_jshq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:open-jam-outline-sharp" /></template>
<style>
.sk4x_jshq {
  fill: currentColor;
  d: path("M6 21h12v-2h-5v-7.2l1.6 1.6L16 12l-4-4l-4 4l1.4 1.4l1.6-1.6V19H6zm-4-5V3h20v13h-7v-2h5V5H4v9h5v2z");
}

</style>
