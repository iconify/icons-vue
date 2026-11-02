<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0h1046ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-fill-sharp" /></template>
<style>
.u0h1046ow {
  fill: currentColor;
  d: path("M22.874 19.514A1 1 0 0 1 22 21H2a1 1 0 0 1-.874-1.486l10-18a1 1 0 0 1 1.748 0Z");
}

</style>
