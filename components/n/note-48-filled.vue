<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c8n953hnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:note-48-filled" /></template>
<style>
.c8n953hnj {
  fill: currentColor;
  d: path("M12.25 6A6.25 6.25 0 0 0 6 12.25v23.5A6.25 6.25 0 0 0 12.25 42H26v-9.75A6.25 6.25 0 0 1 32.25 26H42V12.25A6.25 6.25 0 0 0 35.75 6zm29.197 22.5H32.25a3.75 3.75 0 0 0-3.75 3.75v9.197a6.3 6.3 0 0 0 1.848-1.278l9.821-9.82a6.3 6.3 0 0 0 1.278-1.849");
}

</style>
