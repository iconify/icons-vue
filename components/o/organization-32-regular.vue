<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dza0f1bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:organization-32-regular" /></template>
<style>
.dza0f1bzq {
  fill: currentColor;
  d: path("M16 2a5 5 0 0 0-1.001 9.9v3.099H9.733A2.733 2.733 0 0 0 7 17.732V20.1A5.002 5.002 0 0 0 8 30a5 5 0 0 0 1-9.9v-2.368c0-.405.329-.733.733-.733h12.534c.405 0 .733.328.733.733V20.1a5.002 5.002 0 0 0 1 9.9a5 5 0 0 0 1-9.9v-2.368a2.733 2.733 0 0 0-2.733-2.733H17V11.9A5.002 5.002 0 0 0 16 2m-3 5a3 3 0 1 1 6 0a3 3 0 0 1-6 0M5 25a3 3 0 1 1 6 0a3 3 0 0 1-6 0m19-3a3 3 0 1 1 0 6a3 3 0 0 1 0-6");
}

</style>
