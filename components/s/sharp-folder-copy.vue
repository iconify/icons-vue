<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu6d72pit"/><path class="h1vmt1quk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-folder-copy" /></template>
<style>
.h1vmt1quk {
  fill: currentColor;
  d: path("M23 4h-9l-2-2H5.01L5 17h18z");
}

.mu6d72pit {
  fill: currentColor;
  d: path("M3 6H1v15h19v-2H3z");
}

</style>
