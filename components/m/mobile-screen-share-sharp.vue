<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wny1-3g8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-screen-share-sharp" /></template>
<style>
.wny1-3g8e {
  fill: currentColor;
  d: path("M9.5 14.808V11h3.692V9.692L15 11.5l-1.808 1.808V12H10.5v2.808zM6 22V2h12v20zm1-3.5h10v-13H7z");
}

</style>
