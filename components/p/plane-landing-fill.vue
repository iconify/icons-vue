<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw61tvbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-fill" /></template>
<style>
.yw61tvbzn {
  fill: currentColor;
  d: path("M17.707 11.293c1.536 1.536 2.951 3.462 1 5.414c-.692.692-1.538 1.096-2.528.899c-1.102-.221-2.116-1.128-2.886-1.899l-1.636-1.636l-4.985.831a2 2 0 0 1-1.743-.559l-.136-.136a1.614 1.614 0 0 1 .173-2.431l2.766-2.075L7.382 9h-.968A2 2 0 0 1 5 8.414l-.207-.207a1.706 1.706 0 0 1 0-2.414l3-3a1.706 1.706 0 0 1 2.414 0l.207.207A2 2 0 0 1 11 4.414v.968l.701.35l2.075-2.766a1.615 1.615 0 0 1 2.431-.173l.136.136a2 2 0 0 1 .559 1.743l-.831 4.985ZM21 20a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
