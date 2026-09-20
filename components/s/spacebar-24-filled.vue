<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvgoyfbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:spacebar-24-filled" /></template>
<style>
.vvgoyfbck {
  fill: currentColor;
  d: path("M20 11v2H4v-2a1 1 0 1 0-2 0v2a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2v-2a1 1 0 1 0-2 0");
}

</style>
