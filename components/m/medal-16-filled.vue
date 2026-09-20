<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="heu25acvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:medal-16-filled" /></template>
<style>
.heu25acvl {
  fill: currentColor;
  d: path("M8 9a3 3 0 1 1 0 6a3 3 0 0 1 0-6M4.276 1.151a2.23 2.23 0 0 0 .098 2.312L7.426 8.04A4 4 0 0 0 4.799 9.6l-2.38-3.57A2.5 2.5 0 0 1 2 4.645v-.091a2.5 2.5 0 0 1 .356-1.286l.632-1.054A2.5 2.5 0 0 1 4.276 1.15m7.447 0a2.5 2.5 0 0 1 1.289 1.063l.632 1.054c.233.388.356.833.356 1.286v.09a2.5 2.5 0 0 1-.42 1.387L11.2 9.6a4 4 0 0 0-2.627-1.56l3.053-4.578a2.23 2.23 0 0 0 .097-2.312M9.773 1a1.228 1.228 0 0 1 1.02 1.908L10.067 4H5.934l-.728-1.092A1.229 1.229 0 0 1 6.228 1z");
}

</style>
