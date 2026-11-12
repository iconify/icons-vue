<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpejezcgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-help-corner-fill-sharp" /></template>
<style>
.vpejezcgw {
  fill: currentColor;
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m10 9a3 3 0 1 1 3 3a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 16 16a1 1 0 0 1-2 0m-4-1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1m7 5h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
