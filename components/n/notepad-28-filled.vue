<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ql_mg2bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:notepad-28-filled" /></template>
<style>
.ql_mg2bli {
  fill: currentColor;
  d: path("M19.25 2a.75.75 0 0 1 .75.75V4h.25A2.75 2.75 0 0 1 23 6.75V18h-4.25A2.75 2.75 0 0 0 16 20.75V25H7.75A2.75 2.75 0 0 1 5 22.25V6.75A2.75 2.75 0 0 1 7.75 4H8V2.75a.75.75 0 0 1 1.5 0V4h3.75V2.75a.75.75 0 0 1 1.5 0V4h3.75V2.75a.75.75 0 0 1 .75-.75m3.51 17.5q-.085.136-.2.25l-4.81 4.81q-.114.115-.25.2v-4.01c0-.69.56-1.25 1.25-1.25zM9.75 18a.75.75 0 0 0 0 1.5h3.5l.077-.004a.75.75 0 0 0 0-1.492L13.25 18zm0-4.5a.75.75 0 0 0 0 1.5h8.5l.077-.004a.75.75 0 0 0 0-1.492l-.077-.004zm0-4.5a.75.75 0 0 0 0 1.5h8.5l.077-.004a.75.75 0 0 0 0-1.492L18.25 9z");
}

</style>
