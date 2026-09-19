<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ittkvrbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-turned-in-not" /></template>
<style>
.ittkvrbim {
  fill: currentColor;
  d: path("M19 3H5.01L5 21l7-3l7 3zm-2 15l-5-2.18L7 18V5h10z");
}

</style>
