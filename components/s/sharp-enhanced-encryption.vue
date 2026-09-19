<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gextgbb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-enhanced-encryption" /></template>
<style>
.gextgbb_e {
  fill: currentColor;
  d: path("M20 8h-3V6.22c0-2.61-1.91-4.94-4.51-5.19A4.995 4.995 0 0 0 7 6v2H4v14h16zM8.9 6c0-1.71 1.39-3.1 3.1-3.1s3.1 1.39 3.1 3.1v2H8.9zM16 16h-3v3h-2v-3H8v-2h3v-3h2v3h3z");
}

</style>
