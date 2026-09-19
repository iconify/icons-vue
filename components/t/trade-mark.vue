<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kbeabbcax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:trade-mark" /></template>
<style>
.kbeabbcax {
  fill: currentColor;
  d: path("M2 2v7.529h10.313V34h7.5V9.529h10.312V2zm52.5 0l-6.562 13.177L41.375 2h-7.5v32h7.5V20.823L47.938 34L54.5 20.823V34H62V2z");
}

</style>
