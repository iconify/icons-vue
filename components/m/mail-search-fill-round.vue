<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc9oo_bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-fill-round" /></template>
<style>
.kc9oo_bsn {
  fill: currentColor;
  d: path("m19.321 7.907l2.386 2.386a.999.999 0 1 1-1.414 1.414l-2.386-2.386a3.83 3.83 0 1 1 1.414-1.414M7.707 9.293l-4.03-4.03A4.98 4.98 0 0 1 7 4h3a.998.998 0 0 1 .986 1.164a5 5 0 0 0 .174 2.387A5.1 5.1 0 0 0 12.862 10H12a29 29 0 0 1-1.886-.056a9 9 0 0 1-1.386-.18c-.366-.082-.749-.199-1.021-.471m9.586-2a1.829 1.829 0 1 0-2.587-2.586a1.829 1.829 0 0 0 2.587 2.586m-14.824-.41l3.824 3.824c.548.548 1.251.842 1.999 1.009Q9.561 12 12 12h2c1.244 0 2.581-.295 3.537-1.134c.293-.024.582.082.79.29l1.259 1.258A2 2 0 0 0 21 13a1 1 0 0 1 1 1v1a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5V9c0-.733.158-1.453.469-2.117");
}

</style>
