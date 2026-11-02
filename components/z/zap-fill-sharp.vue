<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3wbyjbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-fill-sharp" /></template>
<style>
.g3wbyjbbx {
  fill: currentColor;
  d: path("M15 3v7h5a1.002 1.002 0 0 1 .707 1.707l-10 10A1 1 0 0 1 9 21v-7H4a1.002 1.002 0 0 1-.707-1.707l10-10A1 1 0 0 1 15 3");
}

</style>
