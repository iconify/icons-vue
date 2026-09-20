<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-1b2fjdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:north-outline" /></template>
<style>
.q-1b2fjdo {
  fill: currentColor;
  d: path("M11.5 21V4.864l-5.158 5.152l-.688-.689L12 2.981l6.346 6.346l-.688.714L12.5 4.883V21z");
}

</style>
