<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boyq9ybtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mention-24-filled" /></template>
<style>
.boyq9ybtd {
  fill: currentColor;
  d: path("M12 2c5.523 0 10 4.477 10 10c0 3.057-1.794 5.009-4 5.009c-1.251 0-2.37-.628-3.104-1.73C14.092 16.318 12.899 17 11.5 17C8.893 17 7 14.632 7 12s1.893-5 4.5-5c.952 0 1.809.316 2.513.846A1 1 0 0 1 16 8v4c0 2.288 1.206 3.009 2 3.009s2-.721 2-3.009a8 8 0 1 0-5.42 7.572c.408-.139.867-.06 1.171.245c.493.493.37 1.323-.284 1.565c-1.08.4-2.248.618-3.467.618c-5.523 0-10-4.477-10-10S6.477 2 12 2m-.5 7C10.24 9 9 10.213 9 12s1.24 3 2.5 3s2.5-1.213 2.5-3s-1.24-3-2.5-3");
}

</style>
