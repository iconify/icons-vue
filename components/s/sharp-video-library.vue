<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iaktu0poq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-video-library" /></template>
<style>
.iaktu0poq {
  fill: currentColor;
  d: path("M4 6H2v16h16v-2H4zm18-4H6v16h16zM12 14.5v-9l6 4.5z");
}

</style>
