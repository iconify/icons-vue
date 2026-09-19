<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg356u0bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-folder-shared" /></template>
<style>
.eg356u0bo {
  fill: currentColor;
  d: path("M22 6H12l-2-2H2v16h20zm-7 3c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2m4 8h-8v-1c0-1.33 2.67-2 4-2s4 .67 4 2z");
}

</style>
