<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgs7wnb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:percent-symbol" /></template>
<style>
.dgs7wnb7e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.5 7q0-3.5 3.5-3.5q1.45 0 2.475 1.025T10.5 7T9.475 9.475T7 10.5q-3.5 0-3.5-3.5m2.567 12.991l13-15q.048-.056.085-.12q.036-.064.06-.134q.023-.07.032-.143q.009-.074.004-.147q-.005-.074-.025-.145q-.019-.072-.052-.138t-.079-.124t-.101-.107q-.056-.048-.12-.085q-.064-.036-.134-.06q-.07-.023-.143-.032q-.074-.009-.147-.004q-.074.005-.145.025q-.072.019-.138.052t-.124.079t-.107.101l-13 15q-.097.113-.145.254t-.036.29t.077.283q.067.133.18.231q.056.048.12.085q.064.036.134.06q.07.023.143.032q.074.009.147.004q.074-.005.145-.025q.072-.019.138-.052t.124-.079t.107-.101M17 13.5q-3.5 0-3.5 3.5t3.5 3.5t3.5-3.5t-3.5-3.5");
}

</style>
