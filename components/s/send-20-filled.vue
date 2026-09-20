<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mpgd55fip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:send-20-filled" /></template>
<style>
.mpgd55fip {
  fill: currentColor;
  d: path("M2.724 2.053a.5.5 0 0 0-.707.576l1.498 5.618a.5.5 0 0 0 .4.364l6.855 1.142c.279.047.279.447 0 .494l-6.854 1.142a.5.5 0 0 0-.401.364l-1.498 5.618a.5.5 0 0 0 .707.576l15-7.5a.5.5 0 0 0 0-.894z");
}

</style>
