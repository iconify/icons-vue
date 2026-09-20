<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g13qvvbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-screen-stop-24-filled" /></template>
<style>
.g13qvvbjr {
  fill: currentColor;
  d: path("M4.25 4h15.5A2.25 2.25 0 0 1 22 6.25v11.5A2.25 2.25 0 0 1 19.75 20H4.25A2.25 2.25 0 0 1 2 17.75V6.25A2.25 2.25 0 0 1 4.25 4m5.03 4.215a.75.75 0 0 0-1.06 1.06l2.72 2.72l-2.72 2.725a.75.75 0 0 0 1.06 1.06L12 13.057l2.724 2.723a.75.75 0 1 0 1.06-1.06l-2.723-2.724l2.723-2.715a.75.75 0 1 0-1.06-1.062l-2.723 2.717z");
}

</style>
