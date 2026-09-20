<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjywkblmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sticky-note-sharp" /></template>
<style>
.tjywkblmi {
  fill: currentColor;
  d: path("M16 21H3V3h18v13zm-1-2l4-4h-4zm-4-3h2v-6h3V8H8v2h3z");
}

</style>
