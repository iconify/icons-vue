<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io1p7oban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-comment-bank" /></template>
<style>
.io1p7oban {
  fill: currentColor;
  d: path("M2 2v20l4-4h16V2zm17 11l-2.5-1.5L14 13V5h5z");
}

</style>
