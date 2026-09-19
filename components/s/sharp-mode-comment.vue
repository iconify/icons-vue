<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce56lbbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-mode-comment" /></template>
<style>
.ce56lbbkn {
  fill: currentColor;
  d: path("M22 2H2v16h16l4 4z");
}

</style>
