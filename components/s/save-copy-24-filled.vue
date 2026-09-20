<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssquqkbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-copy-24-filled" /></template>
<style>
.ssquqkbdp {
  fill: currentColor;
  d: path("M3.504 5.627A2.25 2.25 0 0 0 2 7.75v10A4.25 4.25 0 0 0 6.25 22h10a2.25 2.25 0 0 0 2.123-1.504l-2.097.004H6.25a2.75 2.75 0 0 1-2.75-2.75v-10l.004-.051zM6.754 2a2.25 2.25 0 0 0-2.25 2.25v12.997a2.25 2.25 0 0 0 2.25 2.25H19.75a2.25 2.25 0 0 0 2.25-2.25V4.25A2.25 2.25 0 0 0 19.75 2zm6.496 4.75a.75.75 0 0 1 .743.648L14 7.5V10h2.5a.75.75 0 0 1 .102 1.493l-.102.007H14V14a.75.75 0 0 1-1.493.102L12.5 14v-2.5H10a.75.75 0 0 1-.102-1.493L10 10h2.5V7.5a.75.75 0 0 1 .75-.75");
}

</style>
