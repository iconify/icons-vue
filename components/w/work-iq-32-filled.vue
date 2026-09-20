<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x8v706jbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-32-filled" /></template>
<style>
.x8v706jbb {
  fill: currentColor;
  d: path("M16 3c7.732 0 14 6.268 14 14a8.99 8.99 0 0 1-5 8.059V18.5a5.5 5.5 0 1 0-5.5 5.5h.5a1 1 0 1 0 0-2h-.5a3.5 3.5 0 1 1 3.5-3.5v7c0 .488.1.952.281 1.374l.02.044l.036.082h.002a3.5 3.5 0 0 0 3.161 2h.5a1 1 0 1 1 0 2h-.5a5.5 5.5 0 0 1-5.477-5.001L21 26h-1.5c-1.969 0-3.76-.76-5.098-2H8.25A6.25 6.25 0 0 1 2 17.75V17C2 9.268 8.268 3 16 3");
}

</style>
