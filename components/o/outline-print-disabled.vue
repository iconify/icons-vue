<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7vyfwb1w"/><circle class="x_4dn1n_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-print-disabled" /></template>
<style>
.s7vyfwb1w {
  fill: currentColor;
  d: path("M1.41 1.6L0 3.01L5 8c-1.66 0-3 1.34-3 3v6h4v4h12l2.95 2.96l1.41-1.41zM6 15H4v-4c0-.55.45-1 1-1h2l3 3H6zm2 4v-4h4l4 4zM8 5h8v3h-5.34l2 2H19c.55 0 1 .45 1 1v4l-2 .01V13h-2.34l4 4H22v-6c0-1.66-1.34-3-3-3h-1V3H6v.36l2 2z");
}

.x_4dn1n_l {
  cx: 18px;
  cy: 11.51px;
  r: 1px;
  fill: currentColor;
}

</style>
