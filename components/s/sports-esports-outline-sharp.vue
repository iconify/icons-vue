<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x24fn3ndp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-esports-outline-sharp" /></template>
<style>
.x24fn3ndp {
  fill: currentColor;
  d: path("M2.76 18L4.479 6H19.52l1.72 12h-2.418l-3-3H8.177l-3 3zm2.002-1l3-3h8.482l3 3h.856L18.65 7H5.35L3.906 17zm12.806-4.432q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24M15 9.808q.329 0 .568-.24t.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24m-6.942 2.884h.884v-1.75h1.75v-.884h-1.75v-1.75h-.884v1.75h-1.75v.884h1.75zM12.006 12");
}

</style>
