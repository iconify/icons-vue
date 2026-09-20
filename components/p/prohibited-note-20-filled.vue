<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w91_yu43d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-note-20-filled" /></template>
<style>
.w91_yu43d {
  fill: currentColor;
  d: path("M17.998 10.17L18 10a8 8 0 1 0-8.844 7.956A3 3 0 0 1 9 17v-.576a6.47 6.47 0 0 1-3.035-1.328l1.564-1.565h.001l7.566-7.566A6.47 6.47 0 0 1 16.5 10h.5c.35 0 .686.06.998.17m-3.963-5.266l-9.131 9.131a6.5 6.5 0 0 1 9.131-9.131M10 13a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2zm6.5 3h-4a.5.5 0 1 0 0 1h4a.5.5 0 1 0 0-1m-4-3a.5.5 0 1 0 0 1h4a.5.5 0 1 0 0-1z");
}

</style>
