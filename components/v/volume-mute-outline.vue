<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpm-8qbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:volume-mute-outline" /></template>
<style>
.kpm-8qbob {
  fill: currentColor;
  d: path("M7 15V9h4l5-5v16l-5-5zm2-2h2.85L14 15.15v-6.3L11.85 11H9zm2.5-1");
}

</style>
