<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx8amib4z"/><path class="hd9cndbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-free-breakfast" /></template>
<style>
.hd9cndbxz {
  fill: currentColor;
  d: path("M4 19h16v2H4zM20 3H4v10c0 2.21 1.79 4 4 4h6c2.21 0 4-1.79 4-4v-3h2a2 2 0 0 0 2-2V5c0-1.11-.89-2-2-2m-4 10c0 1.1-.9 2-2 2H8c-1.1 0-2-.9-2-2V5h10zm4-5h-2V5h2z");
}

.rx8amib4z {
  fill: currentColor;
  d: path("M6 13c0 1.1.9 2 2 2h6c1.1 0 2-.9 2-2V5H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
