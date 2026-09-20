<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kuyksc0rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:plus-square-bold" /></template>
<style>
.kuyksc0rf {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176H52V52h152ZM76 128a12 12 0 0 1 12-12h28V88a12 12 0 0 1 24 0v28h28a12 12 0 0 1 0 24h-28v28a12 12 0 0 1-24 0v-28H88a12 12 0 0 1-12-12");
}

</style>
