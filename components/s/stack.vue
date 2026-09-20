<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckxhtsd3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stack" /></template>
<style>
.ckxhtsd3i {
  fill: currentColor;
  d: path("M6.616 14v1h-2q-.672 0-1.144-.475Q3 14.051 3 13.385v-8.77q0-.666.475-1.14T4.615 3h8.77q.666 0 1.14.475T15 4.615v2h-1v-2q0-.269-.173-.442T13.385 4h-8.77q-.269 0-.442.173T4 4.616v8.769q0 .269.173.442t.443.173zm4 7q-.667 0-1.141-.475T9 19.386v-8.77q0-.666.475-1.14T10.615 9h8.77q.666 0 1.14.475t.475 1.14v8.77q0 .666-.475 1.14t-1.14.475z");
}

</style>
