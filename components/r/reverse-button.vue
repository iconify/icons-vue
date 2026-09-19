<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="w7oxpibbt"/><path class="ancmjjdos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:reverse-button" /></template>
<style>
.ancmjjdos {
  fill: var(--svg-color--fff, #fff);
  d: path("M42.736 52.21c2.843-.191 5.216-1.435 6.257-3.135V15.138c-1.045-1.705-3.428-2.947-6.272-3.135L15.21 32.033l27.526 20.17");
}

.w7oxpibbt {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M63.998 57.12a6.877 6.877 0 0 1-6.876 6.882H7.082A6.88 6.88 0 0 1 .208 57.12V7.08A6.876 6.876 0 0 1 7.082.203h50.04c3.8 0 6.876 3.08 6.876 6.877z");
}

</style>
