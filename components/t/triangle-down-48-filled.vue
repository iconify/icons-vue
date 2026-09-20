<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tw6olhx2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-down-48-filled" /></template>
<style>
.tw6olhx2p {
  fill: currentColor;
  d: path("M27.528 40.772c-1.617 2.99-5.915 2.966-7.499-.041L4.495 11.229C3.005 8.4 5.057 5 8.255 5h31.488c3.22 0 5.27 3.44 3.739 6.272z");
}

</style>
