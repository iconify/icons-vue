<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n5_16mrsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cell-add-16-regular" /></template>
<style>
.n5_16mrsi {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M9.25 1c.966 0 1.75.784 1.75 1.75V5h2.25c.966 0 1.75.784 1.75 1.75v.507a5.5 5.5 0 0 0-1.019-.665A.75.75 0 0 0 13.25 6H6v7.25c0 .36.254.659.592.731q.278.55.666 1.019H6.75A1.75 1.75 0 0 1 5 13.25V11H2.75A1.75 1.75 0 0 1 1 9.25v-2.5C1 5.784 1.784 5 2.75 5H5V2.75C5 1.784 5.784 1 6.75 1zm2.25 8a.5.5 0 0 0-.5.5V11H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 0 0 1 0V12h1.5a.5.5 0 0 0 0-1H12V9.5a.5.5 0 0 0-.5-.5M2.75 6a.75.75 0 0 0-.75.75v2.5c0 .414.336.75.75.75H5V6zm4-4a.75.75 0 0 0-.75.75V5h4V2.75A.75.75 0 0 0 9.25 2z");
}

</style>
