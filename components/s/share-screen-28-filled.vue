<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="x7fww_83g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-screen-28-filled" /></template>
<style>
.x7fww_83g {
  d: path("M23.75 5A2.25 2.25 0 0 1 26 7.25v13.5A2.25 2.25 0 0 1 23.75 23H4.25A2.25 2.25 0 0 1 2 20.75V7.25A2.25 2.25 0 0 1 4.25 5zM13.998 8.62a.75.75 0 0 0-.531.22l-3.25 3.255a.75.75 0 0 0 1.061 1.06l1.97-1.973v7.445a.75.75 0 0 0 1.5 0v-7.446l1.974 1.974a.75.75 0 0 0 1.06-1.06L14.529 8.84a.75.75 0 0 0-.53-.22z");
  fill: currentColor;
  fill-rule: nonzero;
}

</style>
