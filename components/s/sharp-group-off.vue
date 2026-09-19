<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv6oqrb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-group-off" /></template>
<style>
.kv6oqrb8h {
  fill: currentColor;
  d: path("M15 8c0-1.42-.5-2.73-1.33-3.76c.42-.14.86-.24 1.33-.24c2.21 0 4 1.79 4 4s-1.79 4-4 4h-.18l-.77-.77c.6-.94.95-2.05.95-3.23m7.83 12H23v-3c0-2.18-3.58-3.47-6.34-3.87c1.1.75 1.95 1.71 2.23 2.94zM7.24 4.41a3.996 3.996 0 0 1 5.35 5.35zM9.17 12H9c-2.21 0-4-1.79-4-4v-.17L.69 3.51L2.1 2.1l19.8 19.8l-1.41 1.41L17 19.83V20H1v-3c0-2.66 5.33-4 8-4c.37 0 .8.03 1.25.08z");
}

</style>
