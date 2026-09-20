<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogunpobou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:outbox-alt-outline-sharp" /></template>
<style>
.ogunpobou {
  fill: currentColor;
  d: path("m6 18l12-6L6 6zm2-3v-2l3-1l-3-1V9l6.5 3zm-5 6V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
