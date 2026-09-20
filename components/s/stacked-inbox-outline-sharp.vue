<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qym0thg-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stacked-inbox-outline-sharp" /></template>
<style>
.qym0thg-t {
  fill: currentColor;
  d: path("M5.5 17.116v-12h16v12zm1-4.424v3.424h14v-3.424h-4.204q-.332.958-1.098 1.48q-.765.52-1.698.52t-1.698-.52t-1.098-1.48zm7 1q.825 0 1.413-.587t.587-1.413h5V6.116h-14v5.576h5q0 .825.588 1.413t1.412.587m3.73 6.424H2.5V7.5h1v11.616h13.73zm-10.73-4h14z");
}

</style>
