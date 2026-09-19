<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkebo3bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-save-as" /></template>
<style>
.nkebo3bvi {
  fill: currentColor;
  d: path("M21 12.4V7l-4-4H3v18h9.4zM15 15c0 1.66-1.34 3-3 3s-3-1.34-3-3s1.34-3 3-3s3 1.34 3 3M6 6h9v4H6zm13.99 10.25l1.77 1.77L16.77 23H15v-1.77zm3.62-.09l-1.2 1.2l-1.77-1.77l1.2-1.2z");
}

</style>
