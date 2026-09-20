<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="irij-ob0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:microwave-16-filled" /></template>
<style>
.irij-ob0t {
  fill: currentColor;
  d: path("M12.5 3A2.5 2.5 0 0 1 15 5.5v5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 1 10.5v-5A2.5 2.5 0 0 1 3.5 3zM4 5a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1zm6 5H4V6h6zM8.5 6.5A.5.5 0 0 0 8 7v2a.5.5 0 0 0 1 0V7a.5.5 0 0 0-.5-.5M13 7.75a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m0-2.5a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

</style>
