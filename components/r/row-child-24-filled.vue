<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i18nxz7fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:row-child-24-filled" /></template>
<style>
.i18nxz7fp {
  fill: currentColor;
  d: path("M5.25 3A2.25 2.25 0 0 0 3 5.25v3a2.25 2.25 0 0 0 2.25 2.25H6v4.25A3.25 3.25 0 0 0 9.25 18H12v.75A2.25 2.25 0 0 0 14.25 21h4.5A2.25 2.25 0 0 0 21 18.75v-3a2.25 2.25 0 0 0-2.25-2.25h-4.5A2.25 2.25 0 0 0 12 15.75v.75H9.25a1.75 1.75 0 0 1-1.75-1.75V10.5h11.25A2.25 2.25 0 0 0 21 8.25v-3A2.25 2.25 0 0 0 18.75 3z");
}

</style>
