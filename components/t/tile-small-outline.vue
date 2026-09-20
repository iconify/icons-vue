<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnm11dboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tile-small-outline" /></template>
<style>
.hnm11dboh {
  fill: currentColor;
  d: path("M3 19v-6h8v6zm10 0v-6h8v6zm-8-2h4v-2H5zm10 0h4v-2h-4zM3 11V5h8v6zm10 0V5h8v6zM5 9h4V7H5zm2-1");
}

</style>
