<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnvmw7yqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-lock-corner-fill-sharp" /></template>
<style>
.lnvmw7yqe {
  fill: currentColor;
  d: path("M21 3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1ZM7.01 6H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 16a1 1 0 0 1 1-1h1a3 3 0 1 1 6 0h1a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-8a1 1 0 0 1-1-1Zm-2-2v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1m6 1h2a1 1 0 0 0-2 0m-8.99 1H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M14 17v3h6v-3Z");
}

</style>
