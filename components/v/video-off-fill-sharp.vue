<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzzgfab5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-off-fill-sharp" /></template>
<style>
.qzzgfab5c {
  fill: currentColor;
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-4.357-4.356A1 1 0 0 1 15 19H3a1 1 0 0 1-1-1V6a1 1 0 0 1 .649-.936L1.293 3.707a.999.999 0 1 1 1.414-1.414m18.511 15.683L8.243 5H15a1 1 0 0 1 1 1v2.382l4.553-2.276A1 1 0 0 1 22 7v10a1 1 0 0 1-.782.976");
}

</style>
