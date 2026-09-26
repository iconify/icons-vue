<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tsrmipadi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-record-sharp-fill" /></template>
<style>
.tsrmipadi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM17 12C17 14.6233 14.6233 17 12 17C9.3767 17 7 14.6233 7 12C7 9.3767 9.3767 7 12 7C14.6233 7 17 9.3767 17 12Z");
}

</style>
