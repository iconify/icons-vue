<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1d7z9_pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-flight-land" /></template>
<style>
.j1d7z9_pi {
  fill: currentColor;
  d: path("M2.5 19h19v2h-19zm16.84-3.15c.8.21 1.62-.26 1.84-1.06c.21-.8-.26-1.62-1.06-1.84l-5.31-1.42l-2.76-9.02L10.12 2v8.28L5.15 8.95l-.93-2.32l-1.45-.39v5.17z");
}

</style>
