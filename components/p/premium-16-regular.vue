<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="inb686g-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:premium-16-regular" /></template>
<style>
.inb686g-h {
  fill: currentColor;
  d: path("M3.5 2a.5.5 0 0 0-.447.276l-2 4a.5.5 0 0 0 .059.54l6.5 8a.5.5 0 0 0 .776 0l6.5-8a.5.5 0 0 0 .06-.54l-2-4A.5.5 0 0 0 12.5 2zM2.309 6l1.5-3h2.05l-.75 3zm.241 1h2.583l1.613 5.164zm3.63 0h3.64L8 12.823zm4.688 0h2.582l-4.196 5.164zm2.823-1h-2.8l-.75-3h2.05zM9.86 6H6.14l.75-3h2.22z");
}

</style>
