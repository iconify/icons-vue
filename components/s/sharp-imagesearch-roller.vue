<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olflweb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-imagesearch-roller" /></template>
<style>
.olflweb3g {
  fill: currentColor;
  d: path("M20 2v6H6V6H4v4h10v5h2v8h-6v-8h2v-3H2V4h4V2z");
}

</style>
