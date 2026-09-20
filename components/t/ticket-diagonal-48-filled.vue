<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="neoqs1b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ticket-diagonal-48-filled" /></template>
<style>
.neoqs1b2v {
  fill: currentColor;
  d: path("M25.204 5.246a4.25 4.25 0 0 1 6.01 0l2.042 2.042c.798.799.592 1.99-.095 2.608a3.5 3.5 0 1 0 4.941 4.941l.123-.123c.642-.585 1.737-.719 2.485.028l2.045 2.046a4.25 4.25 0 0 1 0 6.01l-5.594 5.593l-3.33-3.33a1.25 1.25 0 0 0-1.767 1.767l3.33 3.33l-12.599 12.6a4.25 4.25 0 0 1-6.01 0l-2.044-2.045c-.798-.798-.592-1.992.095-2.61l.131-.122a3.5 3.5 0 1 0-5.073-4.817c-.617.686-1.81.892-2.608.094l-2.041-2.042a4.25 4.25 0 0 1 0-6.01l12.597-12.6l3.333 3.334a1.25 1.25 0 0 0 1.768-1.768L19.61 10.84zm1.627 12.815a1.25 1.25 0 0 0-1.767 1.767l3.111 3.112a1.25 1.25 0 0 0 1.768-1.768z");
}

</style>
