<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5xepabak"/><path class="ccv4j8m1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-dynamic-feed" /></template>
<style>
.ccv4j8m1l {
  fill: currentColor;
  d: path("M22 3H10v10h12zm-2 8h-8V7h8zM4 12H2v9h11v-2H4z");
}

.t5xepabak {
  fill: currentColor;
  d: path("M8 8H6v9h11v-2H8z");
}

</style>
