<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee3s9zbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thumbs-up-double-outline-sharp" /></template>
<style>
.ee3s9zbzs {
  fill: currentColor;
  d: path("M17.825 17L21 9.575V9h-6.3l.475-3.35L13.8 7.025L12.4 5.6L16 2l1.5 1.5L17 7h6v3l-3 7zM1 21V11h5v2H3v6h3v2zm3 0v-9l6-6l1.5 1.5L11 11h6v3l-3 7zm2-2h6.675L15 13.6V13H8.7l.475-3.35L6 12.825zm0 0v-6.175z");
}

</style>
