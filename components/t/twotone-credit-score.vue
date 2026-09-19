<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v574-fbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-credit-score" /></template>
<style>
.v574-fbbc {
  fill: currentColor;
  d: path("M20 4H4c-1.11 0-1.99.89-1.99 2L2 18c0 1.11.89 2 2 2h5v-2H4v-6h18V6c0-1.11-.89-2-2-2m0 4H4V6h16zm-5.07 11.17l-2.83-2.83l-1.41 1.41L14.93 22L22 14.93l-1.41-1.41z");
}

</style>
