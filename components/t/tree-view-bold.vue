<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h45ue2btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tree-view-bold" /></template>
<style>
.h45ue2btj {
  fill: currentColor;
  d: path("M176 156h32a20 20 0 0 0 20-20v-32a20 20 0 0 0-20-20h-32a20 20 0 0 0-20 20v4H92V84h4a20 20 0 0 0 20-20V32a20 20 0 0 0-20-20H64a20 20 0 0 0-20 20v32a20 20 0 0 0 20 20h4v108a28 28 0 0 0 28 28h60v4a20 20 0 0 0 20 20h32a20 20 0 0 0 20-20v-32a20 20 0 0 0-20-20h-32a20 20 0 0 0-20 20v4H96a4 4 0 0 1-4-4v-60h64v4a20 20 0 0 0 20 20M68 36h24v24H68Zm112 160h24v24h-24Zm0-88h24v24h-24Z");
}

</style>
