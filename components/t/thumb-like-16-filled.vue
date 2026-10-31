<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v57_-pb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:thumb-like-16-filled" /></template>
<style>
.v57_-pb9l {
  fill: currentColor;
  d: path("M7.739 1.983c.17-.709.944-1.186 1.672-.905l.001-.002l.001.001l.004.001a1.5 1.5 0 0 1 .277.128c.15.084.347.216.544.412c.402.403.777 1.053.776 2.035c0 .56-.14 1.32-.27 1.906c-.034.158-.073.307-.105.441h.854a2.5 2.5 0 0 1 2.456 2.972l-.614 3.191a3.5 3.5 0 0 1-4.36 2.716l-5.209-1.423a2 2 0 0 1-1.438-1.554l-.296-1.558c-.196-1.027.436-1.954 1.285-2.368C6.28 6.53 7.369 3.513 7.739 1.983");
}

</style>
