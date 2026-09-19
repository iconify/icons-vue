<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvt2f9bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-open-in-full" /></template>
<style>
.jvt2f9bfe {
  fill: currentColor;
  d: path("M21 11V3h-8l3.29 3.29l-10 10L3 13v8h8l-3.29-3.29l10-10z");
}

</style>
