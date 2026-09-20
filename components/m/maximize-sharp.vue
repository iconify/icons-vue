<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzt9ch-wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:maximize-sharp" /></template>
<style>
.yzt9ch-wm {
  fill: currentColor;
  d: path("M5 5V4h14v1z");
}

</style>
