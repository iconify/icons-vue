<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx5og3vdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:missed-video-call" /></template>
<style>
.zx5og3vdg {
  fill: currentColor;
  d: path("m10.7 16l4.5-4.55l-1.4-1.4l-3.1 3.1L8.5 11H10V9H5v5h2v-1.7zM4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h12q.825 0 1.413.588T18 6v4.5l4-4v11l-4-4V18q0 .825-.587 1.413T16 20z");
}

</style>
