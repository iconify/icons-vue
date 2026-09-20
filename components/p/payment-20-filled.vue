<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ofbbqdhhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:payment-20-filled" /></template>
<style>
.ofbbqdhhk {
  fill: currentColor;
  d: path("M4.75 4A2.75 2.75 0 0 0 2 6.75V8h16V6.75A2.75 2.75 0 0 0 15.25 4zM18 9H2v4.25A2.75 2.75 0 0 0 4.75 16h10.5A2.75 2.75 0 0 0 18 13.25zm-4.5 4h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1");
}

</style>
