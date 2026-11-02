<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyodkpvwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-bulk-sharp" /></template>
<style>
.nyodkpvwy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m6.496 3.132l14 8a.999.999 0 0 1 0 1.736l-14 8A1 1 0 0 1 5 20V4a1 1 0 0 1 1.496-.868");
}

</style>
