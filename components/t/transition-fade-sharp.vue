<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2dpm4jom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transition-fade-sharp" /></template>
<style>
.u2dpm4jom {
  fill: currentColor;
  d: path("M3 21V3h7v18zm8-16V3h2v2zm2 2V5h2v2zm2-2V3h2v2zm4 0V3h2v2zm-2 2V5h2v2zm-6 2V7h2v2zm4 0V7h2v2zm4 0V7h2v2zm-6 2V9h2v2zm4 0V9h2v2zm-6 2v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2zm-6 2v-2h2v2zm4 0v-2h2v2zm-6 2v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2zm-6 2v-2h2v2zm4 0v-2h2v2zm-6 2v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2z");
}

</style>
