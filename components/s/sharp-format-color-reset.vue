<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yowz8wbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-format-color-reset" /></template>
<style>
.yowz8wbwk {
  fill: currentColor;
  d: path("M18 14c0-3.98-6-10.8-6-10.8s-1.18 1.35-2.5 3.19l8.44 8.44c.03-.27.06-.55.06-.83M5.41 5.14L4 6.55l3.32 3.32C6.55 11.33 6 12.79 6 14c0 3.31 2.69 6 6 6c1.52 0 2.9-.57 3.95-1.5l2.63 2.63L20 19.72z");
}

</style>
