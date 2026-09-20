<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcypq26xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timer-10-rounded" /></template>
<style>
.dcypq26xy {
  fill: currentColor;
  d: path("M14 16h3V8h-3zm0 3q-1.25 0-2.125-.875T11 16V8q0-1.25.875-2.125T14 5h3q1.25 0 2.125.875T20 8v8q0 1.25-.875 2.125T17 19zM6 8h-.5q-.625 0-1.062-.437T4 6.5t.438-1.062T5.5 5H8q.425 0 .713.288T9 6v11.5q0 .625-.437 1.063T7.5 19t-1.062-.437T6 17.5z");
}

</style>
