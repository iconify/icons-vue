<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hspq9hb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:widget-small" /></template>
<style>
.hspq9hb2b {
  fill: currentColor;
  d: path("M3 21v-5.077h5.077V21zm6.462 0v-5.077h5.077V21zm6.461 0v-5.077H21V21zM3 14.538V9.462h5.077v5.078zm6.462 0V9.462h5.077v5.078zm6.461 0V9.462H21v5.078zM3 8.077V3h5.077v5.077zm6.462 0V3h5.077v5.077zm6.461 0V3H21v5.077z");
}

</style>
