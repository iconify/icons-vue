<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw94dslpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:play-pause-outline" /></template>
<style>
.kw94dslpp {
  fill: currentColor;
  d: path("M5.5 15.239V8.76L10.135 12zm8 .261v-7h1v7zm4 0v-7h1v7z");
}

</style>
