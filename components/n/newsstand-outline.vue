<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p26pxccep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:newsstand-outline" /></template>
<style>
.p26pxccep {
  fill: currentColor;
  d: path("M2.5 19.385v-1h19v1zm2.346-3.77v-7h1v7zm3.77 0v-11h1v11zm3.769 0v-11h1v11zm6.307 0l-3.5-6.115l.866-.5l3.5 6.116z");
}

</style>
