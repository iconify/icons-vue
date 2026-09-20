<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blmvltbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-2-bar" /></template>
<style>
.blmvltbck {
  fill: currentColor;
  d: path("M2 22L22 2v20zm11-2h7V6.85l-7 7z");
}

</style>
