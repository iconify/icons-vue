<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc-k8xkty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-explore" /></template>
<style>
.kc-k8xkty {
  fill: currentColor;
  d: path("M12 10.9c-.61 0-1.1.49-1.1 1.1s.49 1.1 1.1 1.1s1.1-.49 1.1-1.1s-.49-1.1-1.1-1.1M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m2.19 12.19L6 18l3.81-8.19L18 6z");
}

</style>
