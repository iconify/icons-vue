<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t300f1ujq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:seat-window-outline-sharp" /></template>
<style>
.t300f1ujq {
  fill: currentColor;
  d: path("m13.579 9l-1.712-6h7.592l1.712 6zm.75-1h5.519l-1.144-4H13.17zm-8.483-.423q-.69 0-1.191-.501t-.501-1.191t.5-1.192t1.192-.5t1.191.5t.501 1.191q0 .691-.5 1.192t-1.192.501M4.402 20L2 8h1.012l2.2 11h6.75v1zm1.662-2l-1.425-6.796q-.212-1.027.469-1.75T6.7 8.73q.702 0 1.29.419t.749 1.146L9.954 16h4.548l3.402 5.885l-.866.5L14.485 18zm8.265-10L13.17 4z");
}

</style>
