<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tum1a5vmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-low-fill-sharp" /></template>
<style>
.tum1a5vmv {
  fill: currentColor;
  d: path("M12 4v16a1.002 1.002 0 0 1-1.707.707L6.586 17H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3.586l3.707-3.707A1 1 0 0 1 12 4m4.866 5.644c.23.764.345 1.558.345 2.356s-.115 1.592-.345 2.356a8.2 8.2 0 0 1-1.034 2.199a1 1 0 0 1-1.664-1.11a6.21 6.21 0 0 0 0-6.89a1 1 0 0 1 .277-1.387a1 1 0 0 1 1.387.277a8.2 8.2 0 0 1 1.034 2.199");
}

</style>
