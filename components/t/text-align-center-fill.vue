<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6y-vswyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-align-center-fill" /></template>
<style>
.z6y-vswyx {
  fill: currentColor;
  d: path("M20 5a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm-3 4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm3 4a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm-3 4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

</style>
