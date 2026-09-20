<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kl9w3hbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:select-object-20-filled" /></template>
<style>
.kl9w3hbdz {
  fill: currentColor;
  d: path("M6 4.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m11 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m-11 11a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m11 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M7 4.75A.75.75 0 0 1 7.75 4h4.5a.75.75 0 0 1 0 1.5h-4.5A.75.75 0 0 1 7 4.75m0 10.5a.75.75 0 0 1 .75-.75h4.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1-.75-.75m-3-7.5a.75.75 0 0 1 1.5 0v4.5a.75.75 0 0 1-1.5 0zm10.5 0a.75.75 0 0 1 1.5 0v4.5a.75.75 0 0 1-1.5 0z");
}

</style>
