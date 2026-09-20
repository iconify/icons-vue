<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avuxquz_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:notes-outline" /></template>
<style>
.avuxquz_c {
  fill: currentColor;
  d: path("M4 17.27v-1h10v1zm0-4.77v-1h16v1zm0-4.77v-1h16v1z");
}

</style>
