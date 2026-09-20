<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="xc-i6vwwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-screen-stop-28-filled" /></template>
<style>
.xc-i6vwwi {
  fill: currentColor;
  d: path("M4.25 4.999h19.5A2.25 2.25 0 0 1 26 7.249v13.5A2.25 2.25 0 0 1 23.75 23H4.25A2.25 2.25 0 0 1 2 20.75V7.25A2.25 2.25 0 0 1 4.25 5m7.028 5.218a.75.75 0 0 0-1.06 1.06l2.72 2.72l-2.721 2.725a.75.75 0 0 0 1.061 1.06l2.72-2.723l2.724 2.723a.75.75 0 0 0 1.06-1.06l-2.723-2.724l2.723-2.715a.75.75 0 1 0-1.06-1.062l-2.724 2.717z");
}

</style>
