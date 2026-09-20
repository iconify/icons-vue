<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xogrsbcwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-background-effect-horizontal-16-filled" /></template>
<style>
.xogrsbcwz {
  fill: currentColor;
  d: path("M1.168 4c.28-.591.883-1 1.582-1h10.5c.698 0 1.3.409 1.581 1zm4.003 2H1v1h4c0-.35.06-.687.17-1M6 7a2 2 0 1 1 3.998-.002A2 2 0 0 1 6 7m-.236 2H1v1h3.268a2 2 0 0 1 1.507-.988zM4 12H1.168c.28.591.883 1 1.582 1H4zm1-1a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2H5zm7 1v1h1.25c.698 0 1.3-.409 1.581-1zm-.268-2a2 2 0 0 0-1.507-.988L10.236 9H15v1zM11 7h4V6h-4.17c.11.313.17.65.17 1");
}

</style>
