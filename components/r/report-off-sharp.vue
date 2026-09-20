<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up_ux3f5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:report-off-sharp" /></template>
<style>
.up_ux3f5z {
  fill: currentColor;
  d: path("m20.5 23.3l-3.55-3.55l-1.2 1.25h-7.5L3 15.7V8.25l1.2-1.2L.7 3.5l1.4-1.4l19.8 19.8zm-.7-6.35L13 10.2V7h-2v1.2l-3.95-4L8.25 3h7.5L21 8.25v7.45zM12 17q.425 0 .713-.288T13 16v-.15l-.85-.85H12q-.425 0-.712.288T11 16t.288.713T12 17");
}

</style>
