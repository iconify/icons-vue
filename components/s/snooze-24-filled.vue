<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbdtct-my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:snooze-24-filled" /></template>
<style>
.cbdtct-my {
  fill: currentColor;
  d: path("M9 12.504a1 1 0 0 1 .846 1.534l-.065.091L5.08 20H9a1 1 0 0 1 .993.883L10 21a1 1 0 0 1-.883.993L9 22H3a1 1 0 0 1-.846-1.534l.065-.09l4.699-5.872H3a1 1 0 0 1-.993-.883L2 13.504a1 1 0 0 1 .883-.993L3 12.504zM21 2a1 1 0 0 1 .84 1.542l-.066.091L14.109 13h6.89a1 1 0 0 1 .994.883L22 14a1 1 0 0 1-.884.993L21 15h-9a1 1 0 0 1-.84-1.542l.066-.091L18.889 4h-6.89a1 1 0 0 1-.992-.883L11 3a1 1 0 0 1 .883-.993L12 2z");
}

</style>
