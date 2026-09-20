<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cousvdbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-text-title-add-16-filled" /></template>
<style>
.cousvdbcy {
  fill: currentColor;
  d: path("M3 2a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h3.022a5.49 5.49 0 0 1 2.314-5H5a1 1 0 0 1 0-2h6a1 1 0 0 1 1 1v.022a5.5 5.5 0 0 1 3 1.235V4a2 2 0 0 0-2-2zm13 9.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V11H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 0 0 1 0V12h1.5a.5.5 0 0 0 0-1H12z");
}

</style>
