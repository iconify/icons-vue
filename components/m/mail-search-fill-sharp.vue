<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx-bnql3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-fill-sharp" /></template>
<style>
.rx-bnql3k {
  fill: currentColor;
  d: path("m19.321 7.907l2.386 2.386a.999.999 0 1 1-1.414 1.414l-2.386-2.386a3.83 3.83 0 1 1 1.414-1.414M12.862 10H9.414l-6-6H10a.998.998 0 0 1 .986 1.164a5 5 0 0 0 .174 2.387A5.1 5.1 0 0 0 12.862 10m4.431-2.707a1.829 1.829 0 1 0-2.587-2.586a1.829 1.829 0 0 0 2.587 2.586M4 7.414l4.293 4.293A1 1 0 0 0 9 12h6c.265 0 .52-.105.707-.293l.633-.633a5 5 0 0 0 1.014-.175a1 1 0 0 1 .973.257l1.259 1.258A2 2 0 0 0 21 13a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5.414Z");
}

</style>
