<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="krb8if-xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-collapse-16-filled" /></template>
<style>
.krb8if-xd {
  fill: currentColor;
  d: path("M13.25 12.5a.75.75 0 0 1 0 1.5h-9.5a.75.75 0 0 1 0-1.5zm-8.75-8a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7M3 7.5a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zM13.25 9a.75.75 0 0 1 0 1.5h-3.5a.75.75 0 0 1 0-1.5zm0-3.5a.75.75 0 0 1 0 1.5h-3.5a.75.75 0 0 1 0-1.5zm0-3.5a.75.75 0 0 1 0 1.5h-9.5a.75.75 0 0 1 0-1.5z");
}

</style>
