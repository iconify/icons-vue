<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjpjqqqhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-cable" /></template>
<style>
.jjpjqqqhc {
  fill: currentColor;
  d: path("M20 5V3h-4v2h-1v5h2v9h-4V3H5v11H3v5h1v2h4v-2h1v-5H7V5h4v16h8V10h2V5z");
}

</style>
