<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf93s9bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stockpot" /></template>
<style>
.qf93s9bor {
  fill: currentColor;
  d: path("M6 20q-1.25 0-2.125-.875T3 17V8h18v9q0 1.25-.875 2.125T18 20zM3 7V5h6V4q0-.425.288-.712T10 3h4q.425 0 .713.288T15 4v1h6v2z");
}

</style>
