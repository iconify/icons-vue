<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e986pqbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:movie-info-outline-sharp" /></template>
<style>
.e986pqbur {
  fill: currentColor;
  d: path("M2 21V3h20v18zm2-2h2v-2H4zm14 0h2v-2h-2zm-7-2h2v-6h-2zm-7-2h2v-2H4zm14 0h2v-2h-2zM4 11h2V9H4zm14 0h2V9h-2zm-6-2q.425 0 .713-.288T13 8t-.288-.712T12 7t-.712.288T11 8t.288.713T12 9M4 7h2V5H4zm14 0h2V5h-2zM8 19h8V5H8zM8 5h8z");
}

</style>
