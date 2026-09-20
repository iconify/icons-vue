<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q5d1dqb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-multiple-16-regular" /></template>
<style>
.q5d1dqb0p {
  fill: currentColor;
  d: path("M13 4c.607.456 1 1.182 1 2v3.5A4.5 4.5 0 0 1 9.5 14H7a2.5 2.5 0 0 1-2-1h4.5A3.5 3.5 0 0 0 13 9.5zM9.5 2A2.5 2.5 0 0 1 12 4.5v5A2.5 2.5 0 0 1 9.5 12h-5A2.5 2.5 0 0 1 2 9.5v-5A2.5 2.5 0 0 1 4.5 2zM3 9v.5A1.5 1.5 0 0 0 4.5 11H5V9zm3 0v2h2V9zm3 0v2h.5A1.5 1.5 0 0 0 11 9.5V9zM3 6v2h2V6zm3 0v2h2V6zm3 0v2h2V6zM4.5 3A1.5 1.5 0 0 0 3 4.5V5h2V3zM6 5h2V3H6zm3 0h2v-.5A1.5 1.5 0 0 0 9.5 3H9z");
}

</style>
