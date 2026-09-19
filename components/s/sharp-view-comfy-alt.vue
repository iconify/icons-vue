<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vay1lqb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-view-comfy-alt" /></template>
<style>
.vay1lqb2c {
  fill: currentColor;
  d: path("M2 4v16h20V4zm9 13H7v-4h4zm0-6H7V7h4zm6 6h-4v-4h4zm0-6h-4V7h4z");
}

</style>
