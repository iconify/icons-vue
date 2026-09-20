<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="nhg98jbbm"/><path class="p-8lt-dic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:usdx" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.nhg98jbbm {
  fill: var(--svg-color--fa9b00, #fa9b00);
  d: path("M11.237 6.938c2.903 0 5.263 2.453 5.263 5.47c0 3.015-2.36 5.217-5.263 5.217h-.921v-2.25h.921c1.663 0 3.016-1.233 3.016-2.968s-1.353-3.22-3.015-3.22H5.813v9.563h-2.25V6.938z");
}

.p-8lt-dic {
  fill: var(--svg-color--242a47, #242a47);
  d: path("M11.677 3c4.83 0 8.76 4.037 8.76 9c0 4.962-3.93 9-8.76 9h-4.74V10.313h2.25v8.437h2.49c3.604 0 6.51-3.04 6.51-6.75s-2.907-6.75-6.51-6.75H6.375V3z");
}

</style>
