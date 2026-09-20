<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cmwc1hbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:midi-16-filled" /></template>
<style>
.cmwc1hbml {
  fill: currentColor;
  d: path("M13.25 3c.966 0 1.75.784 1.75 1.75v6.5A1.75 1.75 0 0 1 13.25 13H2.75A1.75 1.75 0 0 1 1 11.25v-6.5C1 3.784 1.784 3 2.75 3zM2 11.25c0 .414.336.75.75.75h10.5a.75.75 0 0 0 .75-.75V8h-1v2.5a.5.5 0 0 1-1 0V8h-2v2.5a.5.5 0 0 1-1 0V8H7v2.5a.5.5 0 0 1-1 0V8H4v2.5a.5.5 0 0 1-1 0V8H2zM3.5 5a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m2 0a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m5 0a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1z");
}

</style>
