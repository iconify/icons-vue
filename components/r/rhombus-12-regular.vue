<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gtr0cymmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rhombus-12-regular" /></template>
<style>
.gtr0cymmh {
  fill: currentColor;
  d: path("M9.667 2a1.333 1.333 0 0 1 1.23 1.846l-2.18 5.231A1.5 1.5 0 0 1 7.334 10h-5a1.333 1.333 0 0 1-1.23-1.846l2.18-5.231A1.5 1.5 0 0 1 4.666 2zm-5 1a.5.5 0 0 0-.462.308l-2.18 5.23A.333.333 0 0 0 2.333 9h5a.5.5 0 0 0 .462-.308l2.18-5.23A.333.333 0 0 0 9.667 3z");
}

</style>
