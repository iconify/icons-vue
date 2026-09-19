<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4n51fjcs"/><path class="tml_9tvbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-15mp" /></template>
<style>
.k4n51fjcs {
  fill: currentColor;
  d: path("M15 14h1.5v1.5H15z");
}

.tml_9tvbb {
  fill: currentColor;
  d: path("M3 3v18h18V3zm9 7h3V9h-3V5.5h4.5V7h-3v1h3v3.5H12zM7 5.5h3v6H8.5V7H7zm5.5 13H11V14h-1v3H8.5v-3h-1v4.5H6v-6h6.5zM18 17h-3v1.5h-1.5v-6H18z");
}

</style>
