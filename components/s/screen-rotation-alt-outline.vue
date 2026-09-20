<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baodo_bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:screen-rotation-alt-outline" /></template>
<style>
.baodo_bfq {
  fill: currentColor;
  d: path("M12.444 20.246L5.673 13.5H7.1l6.058 6.058q.173.192.442.182q.27-.01.442-.182l5.308-5.308h-3.312v-1h5v5h-1v-3.312l-5.307 5.308q-.46.46-1.143.46t-1.144-.46m-9.482-9.515v-5h1v3.311l5.307-5.307q.46-.46 1.144-.46t1.143.46l6.771 6.746H16.9l-6.058-6.058q-.173-.192-.442-.182q-.27.009-.442.182L4.65 9.731h3.312v1z");
}

</style>
