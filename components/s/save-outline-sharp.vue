<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rob9dmbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:save-outline-sharp" /></template>
<style>
.rob9dmbbj {
  fill: currentColor;
  d: path("M20 7.423V20H4V4h12.577zm-1 .427L16.15 5H5v14h14zm-5.587 8.107q.587-.582.587-1.414t-.582-1.418t-1.413-.586t-1.419.581T10 14.535t.582 1.418t1.414.587t1.417-.582M6.77 9.769h7.423v-3H6.77zM5 7.85V19V5z");
}

</style>
