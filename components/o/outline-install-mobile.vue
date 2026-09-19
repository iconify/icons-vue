<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm2p8eb-o"/><path class="he_sxxb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-install-mobile" /></template>
<style>
.he_sxxb4l {
  fill: currentColor;
  d: path("m18 14l5-5l-1.41-1.41L19 10.17V3h-2v7.17l-2.59-2.58L13 9z");
}

.pm2p8eb-o {
  fill: currentColor;
  d: path("M17 18H7V6h7V4H7V3h7V1.01L7 1c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2v-5h-2zm0 3H7v-1h10z");
}

</style>
