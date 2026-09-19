<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au_sewilm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-party-mode" /></template>
<style>
.au_sewilm {
  fill: currentColor;
  d: path("M20 4h-3.17L15 2H9L7.17 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 14H4V6h4.05l.59-.65L9.88 4h4.24l1.24 1.35l.59.65H20zM9 12c0-1.66 1.34-3 3-3h3.98c-.92-1.21-2.35-2-3.98-2a5.002 5.002 0 0 0-4.9 6h2.08c-.11-.31-.18-.65-.18-1m6 0c0 1.66-1.34 3-3 3H8.02c.92 1.21 2.35 2 3.98 2a5.002 5.002 0 0 0 4.9-6h-2.08c.11.31.18.65.18 1");
}

</style>
