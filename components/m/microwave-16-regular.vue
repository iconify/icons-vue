<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lzi2k4b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:microwave-16-regular" /></template>
<style>
.lzi2k4b3o {
  fill: currentColor;
  d: path("M12.5 3A2.5 2.5 0 0 1 15 5.5v5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 1 10.5v-5A2.5 2.5 0 0 1 3.5 3zm-9 1A1.5 1.5 0 0 0 2 5.5v5A1.5 1.5 0 0 0 3.5 12h9a1.5 1.5 0 0 0 1.5-1.5v-5A1.5 1.5 0 0 0 12.5 4zM10 5a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1zm-6 5h6V6H4zm4.5-3.5A.5.5 0 0 1 9 7v2a.5.5 0 0 1-1 0V7a.5.5 0 0 1 .5-.5m4 1.25a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5m0-2.5a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
