<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn8xx98go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shapes-fill-sharp" /></template>
<style>
.jn8xx98go {
  fill: currentColor;
  d: path("M12.832 9.445A1 1 0 0 1 12 11H4a1 1 0 0 1-.832-1.555l4-6a1 1 0 0 1 1.664 0Zm-.439 5.608a5.001 5.001 0 1 1 9.213 3.896a5.001 5.001 0 0 1-9.213-3.896M9 14a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1Z");
}

</style>
