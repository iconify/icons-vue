<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lamhijb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toggle-off-fill" /></template>
<style>
.lamhijb_l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 5H16C19.866 5 23 8.13401 23 12C23 15.866 19.866 19 16 19H8C4.13401 19 1 15.866 1 12C1 8.13401 4.13401 5 8 5ZM11 12C11 13.6568 9.65685 15 8 15C6.34315 15 5 13.6568 5 12C5 10.3432 6.34315 9 8 9C9.65685 9 11 10.3432 11 12Z");
}

</style>
