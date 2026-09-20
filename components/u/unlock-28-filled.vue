<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="s1t_o8b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:unlock-28-filled" /></template>
<style>
.s1t_o8b8g {
  d: path("M13.288 2.005L13.5 2a4.5 4.5 0 0 1 4.49 4.205a.75.75 0 1 1-1.496.097a3 3 0 0 0-5.989.022L10.5 6.5v2.999l9.25.001A2.25 2.25 0 0 1 22 11.75v12.002a2.25 2.25 0 0 1-2.25 2.25H7.248a2.25 2.25 0 0 1-2.25-2.25V11.75a2.25 2.25 0 0 1 2.25-2.25L9 9.499L9 6.5a4.5 4.5 0 0 1 4.288-4.495L13.5 2l-.212.005zM13.5 16a1.624 1.624 0 1 0 0 3.249a1.624 1.624 0 0 0 0-3.249z");
  fill: currentColor;
  fill-rule: nonzero;
}

</style>
