<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5pwbcbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-ping-fill" /></template>
<style>
.a5pwbcbxs {
  fill: currentColor;
  d: path("M16.236 3.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M5 4c5.579.001 10.663 3.538 12.87 8.617A13.4 13.4 0 0 1 19 18a1 1 0 0 1-2 0c0-1.579-.329-3.14-.964-4.586a12.3 12.3 0 0 0-2.618-3.832C11.185 7.35 8.173 6.001 5 6a1 1 0 0 1 0-2m0 6c2.136 0 4.189.775 5.707 2.293a7.65 7.65 0 0 1 1.688 2.548A8.3 8.3 0 0 1 13 18a1 1 0 0 1-2 0a6.3 6.3 0 0 0-.457-2.404a5.7 5.7 0 0 0-1.25-1.889C8.153 12.568 6.6 12 5 12a1 1 0 0 1 0-2m-2.764 6.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338");
}

</style>
