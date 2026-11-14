<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="khn5a79eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-visual-16-filled" /></template>
<style>
.khn5a79eh {
  fill: currentColor;
  d: path("M2.75 10a.75.75 0 0 1 .75.75v.5c0 .69.56 1.25 1.25 1.25h.5a.75.75 0 0 1 0 1.5h-.5A2.75 2.75 0 0 1 2 11.25v-.5a.75.75 0 0 1 .75-.75m10.5 0a.75.75 0 0 1 .75.75v.5A2.75 2.75 0 0 1 11.25 14h-.5a.75.75 0 0 1 0-1.5h.5c.69 0 1.25-.56 1.25-1.25v-.5a.75.75 0 0 1 .75-.75M8 5.5a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5M8 7a1 1 0 1 0 0 2a1 1 0 0 0 0-2M5.25 2a.75.75 0 0 1 0 1.5h-.5c-.69 0-1.25.56-1.25 1.25v.5a.75.75 0 0 1-1.5 0v-.5A2.75 2.75 0 0 1 4.75 2zm0 2.5a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5m6-2.5A2.75 2.75 0 0 1 14 4.75v.5a.75.75 0 0 1-1.5 0v-.5c0-.69-.56-1.25-1.25-1.25h-.5a.75.75 0 0 1 0-1.5z");
}

</style>
