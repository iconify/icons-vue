<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm6amu55j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:widget-medium" /></template>
<style>
.zm6amu55j {
  fill: currentColor;
  d: path("M3 21v-5.077h5.077V21zm6.462 0v-5.077h5.077V21zm6.461 0v-5.077H21V21zM3 14.538V9.462h5.077v5.078zm6.462 0V9.462h5.077v5.078zm6.461 0V9.462H21v5.078zM3 8.077V3h11.539v5.077zm12.923 0V3H21v5.077z");
}

</style>
