<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvb6_fp2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:videocam-sharp" /></template>
<style>
.pvb6_fp2b {
  fill: currentColor;
  d: path("M2 20V4h16v6.5l4-4v11l-4-4V20z");
}

</style>
