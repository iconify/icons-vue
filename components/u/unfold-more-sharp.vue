<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="via4fpbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unfold-more-sharp" /></template>
<style>
.via4fpbxb {
  fill: currentColor;
  d: path("m12 20.27l-3.846-3.847l.719-.72L12 18.832l3.127-3.127l.72.719zM8.873 8.32l-.72-.72L12 3.754L15.846 7.6l-.719.72L12 5.191z");
}

</style>
