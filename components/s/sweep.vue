<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2wfuf_9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sweep" /></template>
<style>
.d2wfuf_9d {
  fill: currentColor;
  d: path("M10.5 17.5v-1h5v1zm-4.45-.192L1.08 12.34l.714-.715l4.256 4.256l9.155-9.156l.714.714zM14.5 13.5v-1h5v1zm4-4v-1h5v1z");
}

</style>
