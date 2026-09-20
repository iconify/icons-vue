<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcj7r0boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-group-sharp" /></template>
<style>
.fcj7r0boy {
  fill: currentColor;
  d: path("M2 22V6h2v14h14v2zm4-4V2h16v16zm7-10h7V4h-7z");
}

</style>
