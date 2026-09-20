<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xql4y2x3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xmr" /></template>
<style>
.xql4y2x3i {
  fill: var(--svg-color--f60, #f60);
  d: path("M12 3a8.99 8.99 0 0 1 8.543 11.813h-2.918V7.288l-5.633 5.869l-5.617-5.861v7.517H3.457A8.9 8.9 0 0 1 3 12.008C3 7.03 7.026 3 12 3m.025 12.822l3.912-3.914V16.5h3.749C18.022 19.246 15.254 21.002 12 21c-3.244 0-6.098-1.91-7.686-4.5h3.748v-4.592z");
}

</style>
