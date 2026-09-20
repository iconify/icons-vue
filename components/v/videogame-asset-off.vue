<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcqr89a1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:videogame-asset-off" /></template>
<style>
.zcqr89a1h {
  fill: currentColor;
  d: path("M4.616 17q-.691 0-1.153-.462T3 15.378V8.616q0-.697.466-1.16q.465-.462 1.161-.462h2.367L14.5 14.5h-1.427L2.74 4.167l.714-.713l17.092 17.092l-.713.714l-4.26-4.26zM9.811 7h9.573q.69 0 1.153.463T21 8.623v6.762q0 .592-.35 1.015t-.887.552zm6.981 2.791q-.293.291-.293.707t.291.709t.707.293t.709-.291t.293-.707t-.291-.709t-.707-.293t-.709.291M7.5 14.5h1v-2h2v-1h-2v-2h-1v2h-2v1h2z");
}

</style>
