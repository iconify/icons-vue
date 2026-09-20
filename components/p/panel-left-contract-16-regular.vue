<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u8eu_mnrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-contract-16-regular" /></template>
<style>
.u8eu_mnrg {
  fill: currentColor;
  d: path("m9.707 8.5l.647.647a.5.5 0 0 1-.708.707l-1.5-1.5a.5.5 0 0 1 0-.707l1.5-1.5a.5.5 0 0 1 .708.707l-.647.646h1.791a.5.5 0 0 1 0 1zM4 3a2 2 0 0 0-2 2v6.002a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2zM3 5a1 1 0 0 1 1-1h2.002v8.002H4a1 1 0 0 1-1-1zm4.002 7.002V4H12a1 1 0 0 1 1 1v6.002a1 1 0 0 1-1 1z");
}

</style>
