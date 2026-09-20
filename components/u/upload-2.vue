<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzrmx8arg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:upload-2" /></template>
<style>
.jzrmx8arg {
  fill: currentColor;
  d: path("M4 22v-2h16v2zm5-4v-7H5l7-9l7 9h-4v7z");
}

</style>
