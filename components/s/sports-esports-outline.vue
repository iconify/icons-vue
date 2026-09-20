<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm1baqqom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-esports-outline" /></template>
<style>
.rm1baqqom {
  fill: currentColor;
  d: path("M4.512 18q-.756 0-1.177-.551t-.323-1.23L4.1 8.604q.167-1.135.991-1.87Q5.916 6 7.05 6h9.9q1.135 0 1.959.735q.824.734.991 1.869l1.089 7.615q.098.679-.323 1.23T19.489 18q-.333 0-.6-.101t-.508-.341L15.823 15H8.177l-2.558 2.558q-.24.24-.507.341t-.6.101m.4-1.15L7.762 14h8.477l2.85 2.85q.05.05.361.15q.275 0 .438-.163T20 16.4l-1.1-7.7q-.1-.725-.66-1.212Q17.68 7 16.95 7h-9.9q-.73 0-1.29.488q-.56.487-.66 1.212L4 16.4q-.05.275.113.438T4.55 17q.089 0 .362-.15m12.656-4.282q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24m-2-3q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24m-7.51 3.124h.884v-1.75h1.75v-.884h-1.75v-1.75h-.884v1.75h-1.75v.884h1.75zM12 12");
}

</style>
