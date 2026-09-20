<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uo4-vm_7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-one-quarter-16-filled" /></template>
<style>
.uo4-vm_7a {
  fill: currentColor;
  d: path("m6 4.52l-.327.663l-3.401.495a.898.898 0 0 0-.5 1.535l2.462 2.399l-.581 3.387a.899.899 0 0 0 1.306.949L6 13.401z");
}

</style>
