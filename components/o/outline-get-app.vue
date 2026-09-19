<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy6vjcb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-get-app" /></template>
<style>
.zy6vjcb_z {
  fill: currentColor;
  d: path("M13 5v6h1.17L12 13.17L9.83 11H11V5zm2-2H9v6H5l7 7l7-7h-4zm4 15H5v2h14z");
}

</style>
