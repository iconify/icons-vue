<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg-ar89au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:partner-reports" /></template>
<style>
.wg-ar89au {
  fill: currentColor;
  d: path("M11.509 16.415q-.201-.201-.201-.492q0-.29.2-.491q.202-.201.492-.201t.491.2q.201.202.201.492t-.2.492q-.201.2-.492.2t-.491-.2m-.009-3.569V4h1v8.846zM5.616 20q-.691 0-1.153-.462T4 18.384v-2.423h1v2.423q0 .231.192.424t.423.192h12.77q.23 0 .423-.192t.192-.424v-2.423h1v2.423q0 .691-.462 1.153T18.384 20z");
}

</style>
