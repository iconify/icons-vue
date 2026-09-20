<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="riyerkbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unknown-med-sharp" /></template>
<style>
.riyerkbte {
  fill: currentColor;
  d: path("M3 12.5v-2h8v2zm9.98 0v-2h8v2z");
}

</style>
