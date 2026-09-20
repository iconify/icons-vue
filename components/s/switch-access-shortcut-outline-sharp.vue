<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iszng7lai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-access-shortcut-outline-sharp" /></template>
<style>
.iszng7lai {
  fill: currentColor;
  d: path("M15 22q-3.175-1.2-5.087-3.95T8 11.9q0-2.275.9-4.312T11.45 4H8V2h7v7h-2V5.3q-1.425 1.275-2.212 2.988T10 11.9q0 2.55 1.35 4.688T15 19.825z");
}

</style>
