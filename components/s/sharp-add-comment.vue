<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbws55bcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-add-comment" /></template>
<style>
.jbws55bcr {
  fill: currentColor;
  d: path("M22 2H2v16h16l4 4zm-5 9h-4v4h-2v-4H7V9h4V5h2v4h4z");
}

</style>
