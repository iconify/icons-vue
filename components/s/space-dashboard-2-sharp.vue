<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwf_jbcay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:space-dashboard-2-sharp" /></template>
<style>
.mwf_jbcay {
  fill: currentColor;
  d: path("M21 21V3zM3 21h10V3H3zm12 0h6v-8h-6zm0-10h6V3h-6z");
}

</style>
