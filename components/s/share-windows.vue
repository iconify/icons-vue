<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4z1n5enz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:share-windows" /></template>
<style>
.y4z1n5enz {
  fill: currentColor;
  d: path("M7 15V9q0-.825.588-1.412T9 7h8.15l-2.575-2.575L16 3l5 5l-5 5l-1.425-1.4L17.15 9H9v6zm-2 6q-.825 0-1.412-.587T3 19V4h2v15h12v-4h2v4q0 .825-.587 1.413T17 21z");
}

</style>
