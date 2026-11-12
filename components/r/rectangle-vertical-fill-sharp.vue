<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0o6266pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rectangle-vertical-fill-sharp" /></template>
<style>
.z0o6266pd {
  fill: currentColor;
  d: path("M6 21V3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1");
}

</style>
