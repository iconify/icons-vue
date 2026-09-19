<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwjuerb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-folder" /></template>
<style>
.vwjuerb_o {
  fill: currentColor;
  d: path("M10 4H2v16h20V6H12z");
}

</style>
