<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ie8olfbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-horizontal-48-filled" /></template>
<style>
.ie8olfbyc {
  fill: currentColor;
  d: path("M16 24a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0m11.5 0a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0m8 3.5a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

</style>
