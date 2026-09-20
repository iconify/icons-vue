<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-43ddoew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-null-outline-sharp" /></template>
<style>
.w-43ddoew {
  fill: currentColor;
  d: path("M3 21L21 3v18zm2.421-1H20V5.427z");
}

</style>
