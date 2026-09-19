<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbhd2_bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-north-east" /></template>
<style>
.fbhd2_bau {
  fill: currentColor;
  d: path("M9 5v2h6.59L4 18.59L5.41 20L17 8.41V15h2V5z");
}

</style>
