<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufn74cc3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-size-24-filled" /></template>
<style>
.ufn74cc3l {
  fill: currentColor;
  d: path("M2 6.75A2.75 2.75 0 0 1 4.75 4h14.5A2.75 2.75 0 0 1 22 6.75v10.5A2.75 2.75 0 0 1 19.25 20H4.75A2.75 2.75 0 0 1 2 17.25zm14.78.47a.75.75 0 0 0-.53-.22h-2.5a.75.75 0 0 0 0 1.5h.69l-1.72 1.719a.75.75 0 1 0 1.06 1.06L15.5 9.56v.69a.75.75 0 0 0 1.5 0v-2.5a.75.75 0 0 0-.22-.53M7.75 17h2.501a.75.75 0 0 0 0-1.5h-.69l1.72-1.72a.75.75 0 0 0-1.061-1.06L8.5 14.438v-.69a.75.75 0 0 0-1.5 0v2.5a.75.75 0 0 0 .75.75");
}

</style>
