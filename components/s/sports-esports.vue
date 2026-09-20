<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk7g-e0uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-esports" /></template>
<style>
.lk7g-e0uu {
  fill: currentColor;
  d: path("M4.512 18q-.756 0-1.177-.551t-.323-1.23L4.1 8.604q.167-1.135.991-1.87Q5.916 6 7.05 6h9.9q1.135 0 1.959.735q.824.734.991 1.869l1.089 7.615q.098.679-.323 1.23T19.489 18q-.333 0-.6-.101t-.508-.341L15.823 15H8.177l-2.558 2.558q-.24.24-.507.341t-.6.101m13.056-5.432q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24m-2-3q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24m-7.51 3.124h.884v-1.75h1.75v-.884h-1.75v-1.75h-.884v1.75h-1.75v.884h1.75z");
}

</style>
