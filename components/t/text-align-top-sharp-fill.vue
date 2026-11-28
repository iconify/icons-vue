<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jp_7kvgoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-align-top-sharp-fill" /></template>
<style>
.jp_7kvgoi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM6 6L6 8L18 8L18 6ZM6 10L6 12L14 12L14 10Z");
}

</style>
