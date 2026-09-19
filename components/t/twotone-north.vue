<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edwti2b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-north" /></template>
<style>
.edwti2b0g {
  fill: currentColor;
  d: path("m5 9l1.41 1.41L11 5.83V22h2V5.83l4.59 4.59L19 9l-7-7z");
}

</style>
