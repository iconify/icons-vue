<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s55k0kb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-sharp-fill" /></template>
<style>
.s55k0kb_s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2C14.071 2 16 3.929 16 6C16 8.071 14.071 10 12 10C9.929 10 8 8.071 8 6C8 3.929 9.929 2 12 2ZM11 12H13C16.728 12 20 15.272 20 19V21C20 21.552 19.552 22 19 22H5C4.448 22 4 21.552 4 21V19C4 15.272 7.272 12 11 12Z");
}

</style>
