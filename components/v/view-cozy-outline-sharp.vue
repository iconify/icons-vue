<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj89sacdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-cozy-outline-sharp" /></template>
<style>
.fj89sacdj {
  fill: currentColor;
  d: path("M3 10.5V3h7.5v7.5zm2-2h3.5V5H5zM3 21v-7.5h7.5V21zm2-2h3.5v-3.5H5zm8.5-8.5V3H21v7.5zm2-2H19V5h-3.5zm-2 12.5v-7.5H21V21zm2-2H19v-3.5h-3.5zm0-3.5");
}

</style>
