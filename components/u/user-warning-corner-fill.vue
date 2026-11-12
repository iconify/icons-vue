<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwcyd5ulv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-warning-corner-fill" /></template>
<style>
.pwcyd5ulv {
  fill: currentColor;
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m14 7v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m-8 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1m7 5h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
