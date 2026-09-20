<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3c8e8bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speaker-3-sharp" /></template>
<style>
.e3c8e8bau {
  fill: currentColor;
  d: path("M8 22v-1H4V2h16v19h-4v1z");
}

</style>
