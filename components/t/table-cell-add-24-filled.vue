<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9h579bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cell-add-24-filled" /></template>
<style>
.a9h579bbz {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M11 17.5c0 1.747.69 3.332 1.812 4.5H10.25A2.25 2.25 0 0 1 8 19.75V17.5zm6.5-3.501a.5.5 0 0 0-.5.5V17h-2.505a.5.5 0 0 0 0 1h2.506v2.504a.5.5 0 0 0 1 0V18h2.496a.5.5 0 0 0 0-1H18v-2.501a.5.5 0 0 0-.5-.5M6.5 16H4.25A2.25 2.25 0 0 1 2 13.75v-3.5A2.25 2.25 0 0 1 4.25 8H6.5zm9.5-4.824A6.51 6.51 0 0 0 11.176 16H8V8h8zM19.75 8A2.25 2.25 0 0 1 22 10.25v2.562A6.48 6.48 0 0 0 17.5 11V8zm-6-6A2.25 2.25 0 0 1 16 4.25V6.5H8V4.25A2.25 2.25 0 0 1 10.25 2z");
}

</style>
