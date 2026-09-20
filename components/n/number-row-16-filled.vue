<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ju7vz0b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-row-16-filled" /></template>
<style>
.ju7vz0b5a {
  fill: currentColor;
  d: path("M1 4a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2zm3 1a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 1 0v-5A.5.5 0 0 0 4 5m5-1a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2zm2 1.5a.5.5 0 0 0 .5.5h.5v1.5h-.5a.5.5 0 0 0-.5.5v2.5a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 0-1H12V8.5h.5A.5.5 0 0 0 13 8V5.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5");
}

</style>
