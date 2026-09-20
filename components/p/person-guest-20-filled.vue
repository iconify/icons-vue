<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dyvrqobrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-guest-20-filled" /></template>
<style>
.dyvrqobrk {
  fill: currentColor;
  d: path("M17 10a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2zm-5.826 1A3 3 0 0 0 11 12v5c0 .283.041.556.114.815A12 12 0 0 1 9 18c-1.855 0-3.583-.386-4.865-1.203C2.833 15.967 2 14.69 2 13c0-1.113.903-2 2.009-2zm3.326 1a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zM9 2a4 4 0 1 1 0 8a4 4 0 0 1 0-8");
}

</style>
