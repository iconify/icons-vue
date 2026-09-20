<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyr6bob_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stat-minus-1-sharp" /></template>
<style>
.iyr6bob_l {
  fill: currentColor;
  d: path("M12 14.702L6.692 9.394l.708-.707L12 13.28l4.6-4.594l.708.707z");
}

</style>
