<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkkq5ibbg"/><path class="g7txtqepp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-edgesensor-low" /></template>
<style>
.g7txtqepp {
  fill: currentColor;
  d: path("M20 10h2v7h-2zM2 7h2v7H2zm14-4.99L8 2c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V4c0-1.1-.9-1.99-2-1.99M16 20H8v-1h8zm0-3H8V7h8zm0-12H8V4h8z");
}

.hkkq5ibbg {
  fill: currentColor;
  d: path("M8 4h8v1H8zm0 15h8v1H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
