<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mo79p7b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:password-32-filled" /></template>
<style>
.mo79p7b3h {
  fill: currentColor;
  d: path("M2 10.5A4.5 4.5 0 0 1 6.5 6h19a4.5 4.5 0 0 1 4.5 4.5v11a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 21.5zm5.707 2.793a1 1 0 0 0-1.414 1.414L7.586 16l-1.293 1.293a1 1 0 1 0 1.414 1.414L9 17.414l1.293 1.293a1 1 0 0 0 1.414-1.414L10.414 16l1.293-1.293a1 1 0 0 0-1.414-1.414L9 14.586zm6.086 0a1 1 0 0 0 0 1.414L15.086 16l-1.293 1.293a1 1 0 0 0 1.414 1.414l1.293-1.293l1.293 1.293a1 1 0 0 0 1.414-1.414L17.914 16l1.293-1.293a1 1 0 0 0-1.414-1.414L16.5 14.586l-1.293-1.293a1 1 0 0 0-1.414 0M22 17a1 1 0 1 0 0 2h3a1 1 0 1 0 0-2z");
}

</style>
