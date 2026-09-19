<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qm8v1mksl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tea" /></template>
<style>
.qm8v1mksl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.95 36.234l7.653-15.878h7.151V42.5H8.83c-2.492 0-3.373-2.884-1.88-6.266m30-8.431l-3.553-7.447h-7.151v7.447zm1.593 3.113l2.507 5.318c1.493 3.381.612 6.266-1.88 6.266H26.246V30.917zM16.76 15.918l3.473-7.86c1.584-3.411 6.032-3.411 7.799 0l3.29 7.86z");
}

</style>
