<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxpg_bx2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-pause-sharp" /></template>
<style>
.nxpg_bx2g {
  fill: currentColor;
  d: path("M2 22L22 2v11h-9v9zm17 0v-7h2v7zm-4 0v-7h2v7z");
}

</style>
