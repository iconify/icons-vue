<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_n0t7ehr"/><path class="qmuo7ebvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-backup-table" /></template>
<style>
.i_n0t7ehr {
  fill: currentColor;
  d: path("M20 6v14H6v2h16V6z");
}

.qmuo7ebvh {
  fill: currentColor;
  d: path("M18 2H2v16h16zM9 16H4v-5h5zm7 0h-5v-5h5zm0-7H4V4h12z");
}

</style>
