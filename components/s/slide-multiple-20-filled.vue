<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ie12-3sfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-multiple-20-filled" /></template>
<style>
.ie12-3sfd {
  fill: currentColor;
  d: path("M6 3a4 4 0 0 0-4 4v5a2 2 0 0 0 2 2V8a3 3 0 0 1 3-3h8a2 2 0 0 0-2-2zm1 3a2 2 0 0 0-2 2v7a2 2 0 0 0 2 2h9a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2z");
}

</style>
