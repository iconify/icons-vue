<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-i1fwpqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:summarize-sharp" /></template>
<style>
.q-i1fwpqr {
  fill: currentColor;
  d: path("M7 9h2V7H7zm0 4h2v-2H7zm0 4h2v-2H7zm-4 4V3h13l5 5v13zM15 5v4h4z");
}

</style>
