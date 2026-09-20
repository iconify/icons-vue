<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6u8lvb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-right-outline" /></template>
<style>
.g6u8lvb6i {
  fill: currentColor;
  d: path("M5.616 19q-.691 0-1.153-.462T4 17.384V6.616q0-.691.463-1.153T5.616 5h3.5v1h-3.5q-.231 0-.424.192T5 6.616v10.769q0 .23.192.423t.423.192h3.5v1zm5.884 2V3h1v2h5.885q.69 0 1.152.463T20 6.616v10.769q0 .69-.463 1.153T18.385 19H12.5v2zM5 18V6z");
}

</style>
