<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1rfw60cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:weekend-sharp" /></template>
<style>
.q1rfw60cx {
  fill: currentColor;
  d: path("M1 20V10h4v6h14v-6h4v10zm6-6V8H4V4h16v4h-3v6z");
}

</style>
