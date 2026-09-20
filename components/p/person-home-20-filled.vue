<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h3hls50je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-home-20-filled" /></template>
<style>
.h3hls50je {
  fill: currentColor;
  d: path("M13.836 10.252a1 1 0 0 1 1.328 0l3.5 3.111a1 1 0 0 1 .336.747v4.391a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 0-.5-.5h-2a.5.5 0 0 0-.5.5v3a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5v-4.39a1 1 0 0 1 .336-.748zM9.67 12.616c-.427.38-.671.924-.671 1.495v3.849c-1.47-.116-2.817-.495-3.865-1.163C3.833 15.967 3 14.69 3 13c0-1.113.903-2 2.009-2h6.48zM10 2a4 4 0 1 1 0 8a4 4 0 0 1 0-8");
}

</style>
