<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir9ld_spy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playing-cards-fill-sharp" /></template>
<style>
.ir9ld_spy {
  fill: currentColor;
  d: path("M8 2h12a1 1 0 0 1 1 1v14a1 1 0 0 1-2 0V4H8a1 1 0 0 1 0-2M3 21V7a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m9.832-7.555l-2-3a1 1 0 0 0-1.664 0l-2 3a1 1 0 0 0 0 1.11l2 3a1 1 0 0 0 1.664 0l2-3a1 1 0 0 0 0-1.11");
}

</style>
