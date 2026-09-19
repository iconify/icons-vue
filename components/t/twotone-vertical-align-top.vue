<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2y-9b59z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-vertical-align-top" /></template>
<style>
.i2y-9b59z {
  fill: currentColor;
  d: path("M4 3h16v2H4zm4 8h3v10h2V11h3l-4-4z");
}

</style>
