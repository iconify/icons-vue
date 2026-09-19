<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_pw6tbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-branding-watermark" /></template>
<style>
.z_pw6tbco {
  fill: currentColor;
  d: path("M23 3H1v18h22zm-2 16h-9v-6h9z");
}

</style>
