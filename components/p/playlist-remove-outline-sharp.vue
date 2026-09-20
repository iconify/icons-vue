<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt4dvq_na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:playlist-remove-outline-sharp" /></template>
<style>
.bt4dvq_na {
  fill: currentColor;
  d: path("M14.4 22L13 20.6l2.6-2.6l-2.6-2.6l1.4-1.4l2.6 2.6l2.6-2.6l1.4 1.4l-2.6 2.6l2.6 2.6l-1.4 1.4l-2.6-2.6zM3 16v-2h7v2zm0-4v-2h11v2zm0-4V6h11v2z");
}

</style>
