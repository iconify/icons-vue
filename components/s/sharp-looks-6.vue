<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwdt0v2ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-looks-6" /></template>
<style>
.fwdt0v2ci {
  fill: currentColor;
  d: path("M11 15h2v-2h-2zM21 3H3v18h18zm-6 6h-4v2h4v6H9V7h6z");
}

</style>
