<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ntch5wb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-square-32-filled" /></template>
<style>
.ntch5wb8i {
  fill: currentColor;
  d: path("M3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5zm9 3a1.5 1.5 0 1 0-3 0a1.5 1.5 0 0 0 3 0m0 5.5a1.5 1.5 0 1 0-3 0a1.5 1.5 0 0 0 3 0m-1.5 7a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3M14 10.5a1 1 0 0 0 1 1h7a1 1 0 1 0 0-2h-7a1 1 0 0 0-1 1m1 4.5a1 1 0 1 0 0 2h7a1 1 0 1 0 0-2zm-1 6.5a1 1 0 0 0 1 1h7a1 1 0 1 0 0-2h-7a1 1 0 0 0-1 1");
}

</style>
