<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oju7x-bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-picnic-20-regular" /></template>
<style>
.oju7x-bor {
  fill: currentColor;
  d: path("M3.955 15.707a.5.5 0 0 1-.91-.414L4.542 12h1.099zm13-.414a.5.5 0 0 1-.91.414L14.359 12h1.099zM6.55 10h6.9l-1.818-4h1.1l1.818 4h3.95a.5.5 0 0 1 0 1h-17a.5.5 0 0 1 0-1h3.95l1.82-4h1.1zm8.95-6a.5.5 0 0 1 0 1h-11a.5.5 0 0 1 0-1z");
}

</style>
