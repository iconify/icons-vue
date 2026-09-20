<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jej8mub1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:road-cone-32-regular" /></template>
<style>
.jej8mub1g {
  fill: currentColor;
  d: path("M14.77 2a1.5 1.5 0 0 0-1.434 1.064L5.759 28H3a1 1 0 1 0 0 2h26a1 1 0 1 0 0-2h-2.759L18.665 3.064A1.5 1.5 0 0 0 17.229 2zM7.85 28l1.66-5.462a1 1 0 0 0 .491.129h8.5a1 1 0 1 0 0-2h-8.423l.81-2.667H17a1 1 0 1 0 0-2h-5.505l3.646-12h1.718l7.292 24z");
}

</style>
