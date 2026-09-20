<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvmtb5b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-text-sharp" /></template>
<style>
.kvmtb5b3y {
  fill: currentColor;
  d: path("M8.385 11.596h7.307v-1H8.385zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
