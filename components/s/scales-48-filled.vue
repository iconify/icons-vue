<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h5ev8wl2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:scales-48-filled" /></template>
<style>
.h5ev8wl2h {
  fill: currentColor;
  d: path("M40.75 6a1.25 1.25 0 1 1 0 2.5h-3.469l5.62 13.263c.066.154.099.32.099.487a7.5 7.5 0 0 1-15 0c0-.167.033-.333.099-.487L33.719 8.5h-8.446l.456 25.5H35a4 4 0 0 1 0 8H13a4 4 0 0 1 0-8h10.228L22.77 8.5h-8.49l5.62 13.263c.066.154.099.32.099.487a7.5 7.5 0 0 1-15 0c0-.167.033-.333.099-.487L10.719 8.5H7.25a1.25 1.25 0 1 1 0-2.5zM8.138 21h8.724L12.5 10.704zm23 0h8.724L35.5 10.704z");
}

</style>
