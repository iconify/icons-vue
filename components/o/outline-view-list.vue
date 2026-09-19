<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxz5v7tah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-view-list" /></template>
<style>
.gxz5v7tah {
  fill: currentColor;
  d: path("M3 5v14h18V5zm4 2v2H5V7zm-2 6v-2h2v2zm0 2h2v2H5zm14 2H9v-2h10zm0-4H9v-2h10zm0-4H9V7h10z");
}

</style>
