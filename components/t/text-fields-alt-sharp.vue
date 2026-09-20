<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxz_g4lxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-fields-alt-sharp" /></template>
<style>
.gxz_g4lxm {
  fill: currentColor;
  d: path("M2 21v-2h20v2zm17-4V3h1.5v14zM4 17L9.25 3h2.5L17 17h-2.4l-1.25-3.6H7.7L6.4 17zm4.4-5.6h4.2l-2.05-5.8h-.1z");
}

</style>
