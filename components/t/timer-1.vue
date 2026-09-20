<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykifiqb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timer-1" /></template>
<style>
.ykifiqb5b {
  fill: currentColor;
  d: path("M12 19V8H8V5h7v14z");
}

</style>
