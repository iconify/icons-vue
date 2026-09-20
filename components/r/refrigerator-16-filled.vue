<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="emf_fqkqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:refrigerator-16-filled" /></template>
<style>
.emf_fqkqo {
  fill: currentColor;
  d: path("M13 12.5a2.5 2.5 0 0 1-2.5 2.5h-5A2.5 2.5 0 0 1 3 12.5V8h10zM5.5 9a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 1 0v-2a.5.5 0 0 0-.5-.5m5-8A2.5 2.5 0 0 1 13 3.5V7H3V3.5A2.5 2.5 0 0 1 5.5 1zm-5 2a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 1 0v-2a.5.5 0 0 0-.5-.5");
}

</style>
