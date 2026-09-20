<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyq38cc_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:short-text-sharp" /></template>
<style>
.zyq38cc_t {
  fill: currentColor;
  d: path("M5 14.5v-1h8v1zm0-4v-1h14v1z");
}

</style>
