<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8zrwwqiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-bulk" /></template>
<style>
.d8zrwwqiw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m9.543 3.428l10 6a2.998 2.998 0 0 1 0 5.144l-10 6A2.998 2.998 0 0 1 5 18V6a3 3 0 0 1 4.543-2.572");
}

</style>
