<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwkwv0erm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sd-card-alert-outline-sharp" /></template>
<style>
.rwkwv0erm {
  fill: currentColor;
  d: path("M11 17h2v-2h-2zm0-4h2V8h-2zm9 9H4V8l6-6h10zm-2-2V4h-7.15L6 8.85V20zm0 0V4z");
}

</style>
