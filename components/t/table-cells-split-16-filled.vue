<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fqxa3jboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cells-split-16-filled" /></template>
<style>
.fqxa3jboj {
  fill: currentColor;
  d: path("M8 4h5.95a2.5 2.5 0 0 0-2.45-2H8zM7 2H4.5a2.5 2.5 0 0 0-2.45 2H7zm1 12h3.5a2.5 2.5 0 0 0 2.45-2H8zm-1-2H2.05a2.5 2.5 0 0 0 2.45 2H7zm-5-1V5h12v6zm5-5v4h1V6z");
}

</style>
