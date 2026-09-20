<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkbu0cc0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pause-sharp" /></template>
<style>
.vkbu0cc0g {
  fill: currentColor;
  d: path("M14 18V6h3.5v12zm-7.5 0V6H10v12z");
}

</style>
