<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx_mvdvmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screencast-sharp" /></template>
<style>
.fx_mvdvmo {
  fill: currentColor;
  d: path("M2 20V4h20v16Zm12-4v-2h4v2Zm0-3v-2h4v2ZM4 11v7h16v-8h-6V8h6V6h-8v5Z");
}

</style>
