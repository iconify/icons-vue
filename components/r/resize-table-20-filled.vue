<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k8_sxi-wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:resize-table-20-filled" /></template>
<style>
.k8_sxi-wc {
  fill: currentColor;
  d: path("M5 2a3 3 0 0 0-3 3v2.354a4 4 0 0 1 1-.819V5a2 2 0 0 1 2-2h3.5a.5.5 0 0 0 0-1zm10 16h-2.354a4 4 0 0 0 .819-1H15a2 2 0 0 0 2-2v-3.5a.5.5 0 0 1 1 0V15a3 3 0 0 1-3 3M11.5 2a.5.5 0 0 0 0 1H15a2 2 0 0 1 2 2v3.5a.5.5 0 0 0 1 0V5a3 3 0 0 0-3-3zM5 7a3 3 0 0 0-3 3h3zm0 4v3H2v-3zm0 4H2a3 3 0 0 0 3 3zm1 0h3v3H6zm0-1h3v-3H6zm4 1h3a3 3 0 0 1-3 3zm0-4v3h3v-3zm0-1V7a3 3 0 0 1 3 3zM6 7h3v3H6z");
}

</style>
