<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo1iwy7to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stylus-pencil-outline-rounded" /></template>
<style>
.fo1iwy7to {
  fill: currentColor;
  d: path("M7.45 16q-.525 0-.825-.425t-.1-.925l4.25-11.05q.125-.275.363-.438T11.65 3h.7q.275 0 .513.163t.362.437l4.25 11.05q.2.5-.1.925T16.55 16zm1.45-2h6.2L12 5.975zm0 0h6.2zm-3.525 7q-.5 0-.812-.413t-.138-.912l.125-.3q.2-.625.725-1T6.45 18h11.1q.65 0 1.175.375t.725 1l.125.3q.175.5-.137.913t-.813.412z");
}

</style>
