<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bdm_zstbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-exclude-sharp-fill" /></template>
<style>
.bdm_zstbq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2L15 2C15.5523 2 16 2.4477 16 3L16 8L21 8C21.5523 8 22 8.4477 22 9L22 21C22 21.5523 21.5523 22 21 22L9 22C8.4477 22 8 21.5523 8 21L8 16L3 16C2.4477 16 2 15.5523 2 15L2 3C2 2.4477 2.4477 2 3 2ZM12 10L12 8L9 8C8.4477 8 8 8.4477 8 9L8 12L10 12L10 10ZM16 12L14 12L14 14L12 14L12 16L15 16C15.5523 16 16 15.5523 16 15Z");
}

</style>
