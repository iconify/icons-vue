<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0db6p2uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:scanner-outline-sharp" /></template>
<style>
.e0db6p2uj {
  fill: currentColor;
  d: path("M17.6 12L3.5 6.9L4.2 5L21 11.15V20H3v-8zm1.4 6v-4H5v4zm-9-1h8v-2h-8zm-5 1v-4zm1-1h2v-2H6z");
}

</style>
