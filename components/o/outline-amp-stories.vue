<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrc_nmb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-amp-stories" /></template>
<style>
.hrc_nmb9r {
  fill: currentColor;
  d: path("M7 19h10V4H7zM9 6h6v11H9zM3 6h2v11H3zm16 0h2v11h-2z");
}

</style>
