<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blt1skb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:outpatient-outline-sharp" /></template>
<style>
.blt1skb6s {
  fill: currentColor;
  d: path("M1 21V3h14v18H9v-4H7v4zm2-2h2v-4h6v4h2V5H3zm2-6h2v-2H5zm0-4h2V7H5zm4 4h2v-2H9zm0-4h2V7H9zm10.5 6.5l-1.4-1.4l1.075-1.1H16v-2h3.175L18.1 9.9l1.4-1.4L23 12zM5 19v-4h6v4v-4H5z");
}

</style>
