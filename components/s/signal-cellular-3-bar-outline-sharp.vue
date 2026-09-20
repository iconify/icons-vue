<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2wdg881i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-3-bar-outline-sharp" /></template>
<style>
.z2wdg881i {
  fill: currentColor;
  d: path("M3 21L21 3v18zm11.289-1H20V5.427l-5.712 5.712z");
}

</style>
