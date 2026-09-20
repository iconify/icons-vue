<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbluobbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sticky-note-outline-sharp" /></template>
<style>
.dbluobbon {
  fill: currentColor;
  d: path("M16 21H3V3h18v13zm-1-2v-4h4V5H5v14zm-4-3h2v-6h3V8H8v2h3zm-6 3V5z");
}

</style>
