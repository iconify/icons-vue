<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q23hrk4cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:playlist-add-outline" /></template>
<style>
.q23hrk4cv {
  fill: currentColor;
  d: path("M3 16v-2h7v2zm0-4v-2h11v2zm0-4V6h11v2zm13 12v-4h-4v-2h4v-4h2v4h4v2h-4v4z");
}

</style>
