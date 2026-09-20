<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak0nrab9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:widgets" /></template>
<style>
.ak0nrab9l {
  fill: currentColor;
  d: path("M16.65 13L11 7.35l5.65-5.65l5.65 5.65zM3 11V3h8v8zm10 10v-8h8v8zM3 21v-8h8v8z");
}

</style>
