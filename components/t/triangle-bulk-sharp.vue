<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt6yjfbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-bulk-sharp" /></template>
<style>
.nt6yjfbly {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.874 1.514l10 18A1 1 0 0 1 22 21H2a1 1 0 0 1-.874-1.486l10-18a1 1 0 0 1 1.748 0");
}

</style>
