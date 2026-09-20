<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j40ytub2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-16-filled" /></template>
<style>
.j40ytub2t {
  fill: currentColor;
  d: path("M7.5 2a.5.5 0 0 1 0 1h-3A1.5 1.5 0 0 0 3 4.5v7A1.5 1.5 0 0 0 4.5 13h7a1.5 1.5 0 0 0 1.5-1.5v-2a.5.5 0 0 1 1 0v2a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2zm3.28-.95a.5.5 0 0 1 .527.055l4.5 3.5a.5.5 0 0 1 0 .79l-4.5 3.5A.5.5 0 0 1 10.5 8.5V7.025c-2.232.23-3.624 1.973-4.396 3.399l-.157.3A.5.5 0 0 1 5 10.5c0-2.076.518-3.941 1.537-5.3c.938-1.25 2.286-2.047 3.963-2.179V1.5a.5.5 0 0 1 .28-.45");
}

</style>
