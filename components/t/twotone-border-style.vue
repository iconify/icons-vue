<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezk6o7beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-border-style" /></template>
<style>
.ezk6o7beh {
  fill: currentColor;
  d: path("M19 19h2v2h-2zm0-8h2v2h-2zm0 4h2v2h-2zm-4 4h2v2h-2zM3 21h2V5h16V3H3zM19 7h2v2h-2zm-8 12h2v2h-2zm-4 0h2v2H7z");
}

</style>
