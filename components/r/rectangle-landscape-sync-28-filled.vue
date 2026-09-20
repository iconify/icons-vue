<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ws5w723dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rectangle-landscape-sync-28-filled" /></template>
<style>
.ws5w723dm {
  fill: currentColor;
  d: path("M2 7.75A3.75 3.75 0 0 1 5.75 4h16.5A3.75 3.75 0 0 1 26 7.75v6.65A7.5 7.5 0 0 0 14.5 24H5.75A3.75 3.75 0 0 1 2 20.25zM14 19.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0m5.349-4.08A4 4 0 0 1 24 17.313V16.5a.5.5 0 0 1 1 0v2a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1 0-1h.727a2.998 2.998 0 0 0-4.848-.871a.5.5 0 0 1-.707-.707a4 4 0 0 1 1.677-1.003m2.302 8.16A4 4 0 0 1 17 21.687v.814a.5.5 0 0 1-1 0v-2a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-.727a2.998 2.998 0 0 0 4.848.871a.5.5 0 0 1 .707.707a4 4 0 0 1-1.677 1.003");
}

</style>
