<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="abq83vrdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-link-16-filled" /></template>
<style>
.abq83vrdu {
  fill: currentColor;
  d: path("M7 2H4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h2.035A3.5 3.5 0 0 1 9.5 10h4q.255 0 .5.035V5H8.5A1.5 1.5 0 0 1 7 3.5zm7 2a2 2 0 0 0-2-2H8v1.5a.5.5 0 0 0 .5.5zm-4.5 7a2.5 2.5 0 0 0 0 5h.5a.5.5 0 0 0 0-1h-.5a1.5 1.5 0 0 1 0-3h.5a.5.5 0 0 0 0-1zm3.5 0a.5.5 0 0 0 0 1h.5a1.5 1.5 0 0 1 0 3H13a.5.5 0 0 0 0 1h.5a2.5 2.5 0 0 0 0-5zm-4 2.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5");
}

</style>
