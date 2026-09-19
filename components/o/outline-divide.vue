<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr53fh_vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-divide" /></template>
<style>
.yr53fh_vh {
  fill: currentColor;
  d: path("M3 11h18v2H3zm9.003-8a3 3 0 1 1-.006 6a3 3 0 0 1 .006-6M12 5a1 1 0 1 0 0 2a1 1 0 0 0 0-2m.003 10a3 3 0 1 1-.006 6a3 3 0 0 1 .006-6M12 17a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
