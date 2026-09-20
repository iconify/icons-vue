<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pb_g3-b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-home-16-regular" /></template>
<style>
.pb_g3-b3u {
  fill: currentColor;
  d: path("M10.836 6.252a1 1 0 0 1 1.328 0l3.5 3.111a1 1 0 0 1 .336.747v4.391a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 0-.5-.5h-2a.5.5 0 0 0-.5.5v3a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5v-4.39a1 1 0 0 1 .336-.748zM6.67 8.616A2 2 0 0 0 6.34 9H3.5a.5.5 0 0 0-.5.5v.5c0 1.239 1.063 2.568 3 2.913v1.013C3.469 13.547 2 11.752 2 10v-.5A1.5 1.5 0 0 1 3.5 8h3.864zM7 1.5A2.75 2.75 0 1 1 7 7a2.75 2.75 0 0 1 0-5.5m0 1A1.75 1.75 0 1 0 7 6a1.75 1.75 0 0 0 0-3.5");
}

</style>
