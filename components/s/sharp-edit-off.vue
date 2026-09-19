<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="von7m2dzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-edit-off" /></template>
<style>
.von7m2dzu {
  fill: currentColor;
  d: path("m21.41 6.33l-3.75-3.75l-2.53 2.54l3.75 3.75zM1.39 4.22l7.32 7.32L3 17.25V21h3.75l5.71-5.71l7.32 7.32l1.41-1.41L2.81 2.81zm16.42 5.72l-3.75-3.75l-2.52 2.52l3.75 3.75z");
}

</style>
