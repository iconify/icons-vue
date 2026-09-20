<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t-j_asm8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:organization-add-16-filled" /></template>
<style>
.t-j_asm8q {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M7 1a2.5 2.5 0 0 1 .499 4.95V7h.84a5.5 5.5 0 0 0-1.081 1h-2.89A.367.367 0 0 0 4 8.366v1.684A2.501 2.501 0 0 1 3.5 15a2.5 2.5 0 0 1-.5-4.95V8.366C3 7.612 3.613 7 4.367 7H6.5V5.95A2.501 2.501 0 0 1 7 1m4.5 8a.5.5 0 0 0-.5.5V11H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 0 0 1 0V12h1.5a.5.5 0 0 0 0-1H12V9.5a.5.5 0 0 0-.5-.5");
}

</style>
