<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="to4tx7b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:spade-suit" /></template>
<style>
.to4tx7b5w {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M32.799 20.336C32.799 11.456 18 .198 18 .198S3.201 11.456 3.201 20.336c0 6.946 8.175 10.172 12.766 5.173C15.631 29.688 11.247 33 7 33h.5a1.5 1.5 0 1 0 0 3h21a1.5 1.5 0 0 0 0-3h.5c-4.246 0-8.632-3.312-8.967-7.491c4.591 4.999 12.766 1.773 12.766-5.173");
}

</style>
