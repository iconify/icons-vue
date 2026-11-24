<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3sfb8b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-edit-fill-round" /></template>
<style>
.y3sfb8b0r {
  fill: currentColor;
  d: path("M8.963 19.876c-1.802-1.661-3.349-3.669-4.226-5.974A10.9 10.9 0 0 1 4 10a7.98 7.98 0 0 1 2.343-5.657A7.98 7.98 0 0 1 12 2a7.98 7.98 0 0 1 5.657 2.343A7.98 7.98 0 0 1 20 10c-.001 3.878-2.192 7.322-4.963 9.876a20 20 0 0 1-2.482 1.956a1 1 0 0 1-1.11 0a20 20 0 0 1-2.482-1.956M8 11v2a1 1 0 0 0 1 1h2c.265 0 .52-.105.707-.293l4-4a1 1 0 0 0 0-1.414l-2-2a.997.997 0 0 0-1.414 0l-4 4A1 1 0 0 0 8 11");
}

</style>
