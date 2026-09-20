<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dioapeb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:swap-horiz-sharp" /></template>
<style>
.dioapeb7d {
  fill: currentColor;
  d: path("m7 20l-5-5l5-5l1.4 1.425L5.825 14H13v2H5.825L8.4 18.575zm10-6l-1.4-1.425L18.175 10H11V8h7.175L15.6 5.425L17 4l5 5z");
}

</style>
