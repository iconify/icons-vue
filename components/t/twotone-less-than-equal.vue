<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q01z8wb7w"/><path class="gyj9v_mhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-less-than-equal" /></template>
<style>
.gyj9v_mhe {
  fill: currentColor;
  d: path("M18 20.998H6v-2h12z");
}

.q01z8wb7w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 15.5L9.25 10l8.25-5.5l-1-1.5L6 10l10.5 7z");
}

</style>
