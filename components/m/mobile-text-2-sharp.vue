<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfxkwmt0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-text-2-sharp" /></template>
<style>
.nfxkwmt0a {
  fill: currentColor;
  d: path("M8 12h8v-2H8zm1 3.5h6v-2H9zM5 23V1h14v5.1h1v4.8h-1V23z");
}

</style>
