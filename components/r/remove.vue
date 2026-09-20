<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgaa_3bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:remove" /></template>
<style>
.vgaa_3bxl {
  fill: currentColor;
  d: path("M6 12.5v-1h12v1z");
}

</style>
