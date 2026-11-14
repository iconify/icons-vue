<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="u3728rbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-edit-28-filled" /></template>
<style>
.u3728rbbg {
  fill: currentColor;
  d: path("M23.1 14.67a2.286 2.286 0 0 1 3.232 3.232l-7.902 7.903a2.7 2.7 0 0 1-1.247.706l-1.831.458a1.088 1.088 0 0 1-1.319-1.319l.458-1.83c.118-.473.362-.904.706-1.248zm-3.35.83c.3 0 .555.176.676.43l-5.935 5.935a3.7 3.7 0 0 0-.97 1.712L13.167 25H7.5v-8.75a.75.75 0 0 1 .75-.75zM8 8.75A2.25 2.25 0 0 0 10.25 11h6.5A2.25 2.25 0 0 0 19 8.75V3h.215a3.25 3.25 0 0 1 2.298.952l2.535 2.535c.61.61.952 1.436.952 2.298v4.227a3.28 3.28 0 0 0-2.606.95l-.886.885A2.25 2.25 0 0 0 19.75 14H8.25A2.25 2.25 0 0 0 6 16.25v8.74a3.25 3.25 0 0 1-3-3.24V6.25A3.25 3.25 0 0 1 6.25 3H8zm9.5 0a.75.75 0 0 1-.75.75h-6.5a.75.75 0 0 1-.75-.75V3h8z");
}

</style>
