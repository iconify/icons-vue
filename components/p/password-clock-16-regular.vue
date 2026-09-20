<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ngz9lq4es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:password-clock-16-regular" /></template>
<style>
.ngz9lq4es {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0 2a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5H13a.5.5 0 0 0 0-1h-1V9.5a.5.5 0 0 0-.5-.5m0-7A2.5 2.5 0 0 1 14 4.5v2.1a5.5 5.5 0 0 0-1-.392V4.5A1.5 1.5 0 0 0 11.5 3h-9A1.5 1.5 0 0 0 1 4.5v4A1.5 1.5 0 0 0 2.5 10h3.708a5.5 5.5 0 0 0-.185 1H2.5A2.5 2.5 0 0 1 0 8.5v-4A2.5 2.5 0 0 1 2.5 2zM4.146 5.146a.5.5 0 1 1 .708.708l-.647.646l.647.646a.5.5 0 1 1-.708.708L3.5 7.207l-.646.647a.5.5 0 1 1-.708-.708l.647-.646l-.647-.646a.5.5 0 1 1 .708-.708l.646.647zm4 0a.5.5 0 1 1 .708.708l-.647.646l.353.353q-.43.27-.8.615l-.26-.261l-.646.647a.5.5 0 1 1-.708-.708l.647-.646l-.647-.646a.5.5 0 1 1 .708-.708l.646.647z");
}

</style>
