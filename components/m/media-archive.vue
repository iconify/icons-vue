<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr7m--bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:media-archive" /></template>
<style>
.yr7m--bmk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 3.25h14.5q1.036 0 1.768.732t.732 1.768v1q0 1.036-.732 1.768q-.35.349-.768.532v9.45q0 2.25-2.25 2.25H6q-2.25 0-2.25-2.25V9.123q-1.5-.437-1.5-2.373v-1q0-2.5 2.5-2.5m.5 6v9.25q0 .75.75.75h12q.75 0 .75-.75V9.25zm7.327 2.551l.868.472q1.173.64 1.173 1.976t-1.173 1.976l-.868.473q-1.124.613-2.226-.041T9.25 14.723v-.946q0-1.281 1.101-1.935t2.226-.041");
}

</style>
