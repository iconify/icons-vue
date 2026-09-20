<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pyz4k56tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-checkmark-48-filled" /></template>
<style>
.pyz4k56tm {
  fill: currentColor;
  d: path("M12 6h10.75v16.75H6V12a6 6 0 0 1 6-6M6 25.25h16.75V42H12a6 6 0 0 1-6-6zm19.25 0V42H36a6 6 0 0 0 6-6V25.25zm0-19.25v16.75H42V12a6 6 0 0 0-6-6zm13.13 25.634l-5.5 5.5a1.25 1.25 0 0 1-1.768 0l-2.746-2.746a1.25 1.25 0 0 1 1.768-1.768l1.862 1.862l4.616-4.616a1.25 1.25 0 0 1 1.768 1.768");
}

</style>
