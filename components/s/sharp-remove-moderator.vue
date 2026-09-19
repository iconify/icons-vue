<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlymj7wru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-remove-moderator" /></template>
<style>
.nlymj7wru {
  fill: currentColor;
  d: path("M20 11.09V5l-8-3l-5.22 1.96l12.09 12.09c.72-1.53 1.13-3.22 1.13-4.96M2.81 2.81L1.39 4.22L4 6.83v4.26c0 5.05 3.41 9.76 8 10.91c1.72-.43 3.28-1.36 4.55-2.62l3.23 3.23l1.41-1.41z");
}

</style>
