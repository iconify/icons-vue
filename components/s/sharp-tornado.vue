<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rftmi0ejo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-tornado" /></template>
<style>
.rftmi0ejo {
  fill: currentColor;
  d: path("M20.11 8L23 3H1l2.89 5zM7.95 15L12 22l4.05-7zm11-5H5.05l1.74 3h10.42z");
}

</style>
