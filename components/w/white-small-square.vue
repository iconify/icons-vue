<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yd_p1x0su"/><path class="um7ljub-s"/><path class="o3mnoob_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:white-small-square" /></template>
<style>
.o3mnoob_g {
  fill: var(--svg-color--fff, #fff);
  d: path("M52.03 41.283c0-1.057-.704-1.409-5.106-1.233c-3.698.176-5.459.529-6.515 1.937c-1.057 1.41-1.41 4.05-1.41 7.397c0 2.289 0 4.402 1.233 4.402c1.585 0 1.585-3.698 2.994-5.811c2.465-4.227 8.804-5.283 8.804-6.692");
}

.um7ljub-s {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M41.113 36h37.681a5.11 5.11 0 0 1 5.106 5.107v37.685a5.11 5.11 0 0 1-5.106 5.107H41.113a5.11 5.11 0 0 1-5.106-5.107V41.283c-.141-2.782 2.007-5.142 4.789-5.283z");
}

.yd_p1x0su {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
  d: path("M41.113 36h45.78A5.11 5.11 0 0 1 92 41.107v45.786A5.11 5.11 0 0 1 86.894 92H41.113a5.11 5.11 0 0 1-5.106-5.107v-45.61c-.141-2.782 2.007-5.142 4.789-5.283z");
}

</style>
