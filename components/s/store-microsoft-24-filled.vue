<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnv8i5buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:store-microsoft-24-filled" /></template>
<style>
.tnv8i5buo {
  fill: currentColor;
  d: path("M8 3.75V6H2.75a.75.75 0 0 0-.75.75v11.5A2.75 2.75 0 0 0 4.75 21h14.5A2.75 2.75 0 0 0 22 18.25V6.75a.75.75 0 0 0-.75-.75H16V3.75A1.75 1.75 0 0 0 14.25 2h-4.5A1.75 1.75 0 0 0 8 3.75m1.75-.25h4.5a.25.25 0 0 1 .25.25V6h-5V3.75a.25.25 0 0 1 .25-.25M8 13V9.5h3.5V13zm0 4.5V14h3.5v3.5zm8-4.5h-3.5V9.5H16zm-3.5 4.5V14H16v3.5z");
}

</style>
