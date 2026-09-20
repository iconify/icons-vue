<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqiq5cd_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tile-small" /></template>
<style>
.dqiq5cd_q {
  fill: currentColor;
  d: path("M3 19v-6h8v6zm10 0v-6h8v6zM3 11V5h8v6zm10 0V5h8v6z");
}

</style>
