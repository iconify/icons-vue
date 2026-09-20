<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtwwe_b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:resume-outline-sharp" /></template>
<style>
.rtwwe_b8w {
  fill: currentColor;
  d: path("M6 18V6h2v12zm4 0l10-6l-10-6zm2-3.525v-4.95L16.125 12zM12 12");
}

</style>
