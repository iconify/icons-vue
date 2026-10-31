<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="imzbzob-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:thumb-dislike-16-filled" /></template>
<style>
.imzbzob-s {
  fill: currentColor;
  d: path("M8.976 1.12a3.5 3.5 0 0 1 4.36 2.716l.612 3.192a2.5 2.5 0 0 1-2.455 2.971h-.854c.032.134.07.283.105.442c.13.586.27 1.346.27 1.905c0 .982-.374 1.632-.776 2.035a2.5 2.5 0 0 1-.733.506l-.08.031l-.008.003l-.004.001v.001l-.002-.002c-.729.281-1.502-.196-1.672-.904c-.37-1.53-1.46-4.547-4.422-5.993c-.849-.415-1.481-1.342-1.285-2.368l.296-1.558a2 2 0 0 1 1.438-1.555z");
}

</style>
