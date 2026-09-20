<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwqa1zrdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-file-outline" /></template>
<style>
.dwqa1zrdv {
  fill: currentColor;
  d: path("M9 18h4q.425 0 .713-.288T14 17v-1l2 1.05v-4.1L14 14v-1q0-.425-.288-.712T13 12H9q-.425 0-.712.288T8 13v4q0 .425.288.713T9 18m-3 4q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h8l6 6v12q0 .825-.587 1.413T18 22zm7-13V4H6v16h12V9zM6 4v5zv16z");
}

</style>
