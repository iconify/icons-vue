<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pb5497bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-multiple-20-filled" /></template>
<style>
.pb5497bak {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2H6v2.5A1.5 1.5 0 0 0 7.5 6H15v6.5a2.5 2.5 0 0 1-2.5 2.5h-8A2.5 2.5 0 0 1 2 12.5zm5 0V2h5.5A2.5 2.5 0 0 1 15 4.5V5H7.5a.5.5 0 0 1-.5-.5M7.5 18a2.5 2.5 0 0 1-2.45-2h7.45a3.5 3.5 0 0 0 3.5-3.5V5.05a2.5 2.5 0 0 1 2 2.45V14a4 4 0 0 1-4 4z");
}

</style>
