<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbds0hb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-text-title-checkmark-24-filled" /></template>
<style>
.rbds0hb_o {
  fill: currentColor;
  d: path("M4.75 4A2.75 2.75 0 0 0 2 6.75v10.5A2.75 2.75 0 0 0 4.75 20h6.748A6.5 6.5 0 0 1 22 12.81V6.75A2.75 2.75 0 0 0 19.25 4zM7.5 8h9a1.5 1.5 0 0 1 0 3h-9a1.5 1.5 0 0 1 0-3M23 17.5a5.5 5.5 0 1 1-11 0a5.5 5.5 0 0 1 11 0m-6.146 2.354l4-4a.5.5 0 0 0-.708-.708L16.5 18.793l-1.646-1.647a.5.5 0 0 0-.708.708l2 2a.5.5 0 0 0 .708 0");
}

</style>
