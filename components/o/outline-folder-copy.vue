<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmy_1zbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-folder-copy" /></template>
<style>
.vmy_1zbdh {
  fill: currentColor;
  d: path("M3 19h17v2H3c-1.1 0-2-.9-2-2V6h2zM23 6v9c0 1.1-.9 2-2 2H7c-1.1 0-2-.9-2-2l.01-11c0-1.1.89-2 1.99-2h5l2 2h7c1.1 0 2 .9 2 2M7 15h14V6h-7.83l-2-2H7z");
}

</style>
