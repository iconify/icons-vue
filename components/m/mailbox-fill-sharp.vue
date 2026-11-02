<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhya7nbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mailbox-fill-sharp" /></template>
<style>
.jhya7nbxr {
  fill: currentColor;
  d: path("M18 8h3a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-9v-9a5.01 5.01 0 0 0-4-4.901V8h8V3a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2h-3Zm-8 5v9H3a1 1 0 0 1-1-1v-8a5.01 5.01 0 0 1 4-4.901V9a1 1 0 0 0 1 1a3 3 0 0 1 3 3");
}

</style>
