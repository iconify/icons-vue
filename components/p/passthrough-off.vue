<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdzipsbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:passthrough-off" /></template>
<style>
.vdzipsbcz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 2.75h12q3.25 0 3.25 3.25v6q0 .649-.13 1.169Q18.97 13 18.25 13q-2.175 0-3.712 1.538q-.341.34-.606.712h-.682q-.095 0-.186-.024q-.092-.023-.175-.069q-.083-.045-.152-.11t-.12-.144L11.088 12.5H9.912l-1.529 2.403q-.051.079-.12.144t-.152.11t-.175.069t-.186.024H4.5q-3.25 0-3.25-3.25V6q0-3.25 3.25-3.25m13.75 11.5q-4 0-4 4t4 4q1.657 0 2.828-1.172q1.172-1.171 1.172-2.828t-1.172-2.828q-1.171-1.172-2.828-1.172m0 1.5q.638 0 1.161.278l-3.454 3.454q-.207-.512-.207-1.232q0-2.5 2.5-2.5m0 5q-.72 0-1.232-.207l3.454-3.454q.278.523.278 1.161q0 1.036-.732 1.768t-1.768.732");
}

</style>
