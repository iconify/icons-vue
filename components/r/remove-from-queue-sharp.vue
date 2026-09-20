<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_vfi7x7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:remove-from-queue-sharp" /></template>
<style>
.b_vfi7x7s {
  fill: currentColor;
  d: path("M8 12h8v-2H8zm0 9v-2H2V3h20v16h-6v2z");
}

</style>
