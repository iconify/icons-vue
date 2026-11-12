<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0ffv4bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-fill" /></template>
<style>
.v0ffv4bim {
  fill: currentColor;
  d: path("m19.321 7.907l2.386 2.386a.999.999 0 1 1-1.414 1.414l-2.386-2.386a3.83 3.83 0 1 1 1.414-1.414M8.707 9.293l-5-5.001A3 3 0 0 1 5 4h5a.998.998 0 0 1 .986 1.164a5 5 0 0 0 .174 2.387A5.1 5.1 0 0 0 12.862 10H12c-.64 0-1.286-.014-1.92-.107c-.352-.051-.722-.125-1.028-.315a2 2 0 0 1-.345-.285m8.586-2a1.829 1.829 0 1 0-2.587-2.586a1.829 1.829 0 0 0 2.587 2.586M2.292 5.707l5.001 5a3.75 3.75 0 0 0 1.68.994Q10.011 12 12 12h2c.85 0 1.654-.394 2.3-.923q.537-.034 1.054-.178a1 1 0 0 1 .973.257l1.259 1.258A2 2 0 0 0 21 13a1 1 0 0 1 1 1v3a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7c0-.448.099-.889.292-1.293");
}

</style>
