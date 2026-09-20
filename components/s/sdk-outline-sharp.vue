<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xaxzn7pmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sdk-outline-sharp" /></template>
<style>
.xaxzn7pmy {
  fill: currentColor;
  d: path("M3 21V5.8L5.3 3h13.4L21 5.8V21zM5.4 6h13.2l-.85-1H6.25zM5 19h14V8H5zm10.2-5.5l-2.1 2.1l1.45 1.45l3.55-3.55l-3.55-3.55l-1.45 1.45zm-6.35 0l2.1-2.1L9.5 9.95L5.95 13.5l3.55 3.55l1.45-1.45zM5 19V8z");
}

</style>
