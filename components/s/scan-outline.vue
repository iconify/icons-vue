<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dehecfhot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:scan-outline" /></template>
<style>
.dehecfhot {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20v-3h2v3h12v-3h2v3q0 .825-.587 1.413T18 22zM4 11V4q0-.825.588-1.412T6 2h8l6 6v3h-2V9h-5V4H6v7zm-3 4v-2h22v2zm11 2");
}

</style>
