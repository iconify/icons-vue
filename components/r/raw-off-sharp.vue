<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvs4mws4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:raw-off-sharp" /></template>
<style>
.hvs4mws4e {
  fill: currentColor;
  d: path("M19.8 22.6L1.4 4.2l1.4-1.4l18.4 18.4zM18.5 15l-.75-3.05l-.6 2.35l-2.45-2.4L14 9h1.5l.75 3L17 9h1.5l.75 3L20 9h1.5L20 15zm-9.75 0l1.05-4.2L11 12l1.5 1.5h-1.85l-.4 1.5zM3 15V9h5v3.9h-.9L8 15H6.5l-.9-2H4.5v2zm1.5-3.5h2v-1h-2z");
}

</style>
