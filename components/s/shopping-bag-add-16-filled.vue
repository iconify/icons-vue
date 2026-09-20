<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tkuw45b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shopping-bag-add-16-filled" /></template>
<style>
.tkuw45b_u {
  fill: currentColor;
  d: path("M5 3v2h-.5A1.5 1.5 0 0 0 3 6.5V13a2 2 0 0 0 2 2h2.257a5.5 5.5 0 0 1 5.713-8.801A1.5 1.5 0 0 0 11.5 5H11V3a2 2 0 0 0-3-1.732A2 2 0 0 0 5 3m5 2H9V3c0-.351-.09-.682-.25-.969A1.002 1.002 0 0 1 10 3zM8 5H6V3a1 1 0 0 1 2 0zm8 6.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V11H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 0 0 1 0V12h1.5a.5.5 0 0 0 0-1H12z");
}

</style>
