<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kq8f0us4m"/><path class="lsy_xw7jm"/><circle class="wc8hpep6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mymoney-pro" /></template>
<style>
.kq8f0us4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.262 32.494v3.97a5.507 5.507 0 0 1-5.507 5.508H10.007A5.503 5.503 0 0 1 4.5 36.465V20.099a5.507 5.507 0 0 1 5.507-5.507h26.748a5.51 5.51 0 0 1 5.507 5.507v3.97");
}

.lsy_xw7jm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.43 14.636l-1.453-5.008l-19.413 4.966m15.538-3.975l-2.114-4.591l-17.112 8.566m17.702 9.131h10.43a2.494 2.494 0 0 1 2.492 2.493v4.13a2.494 2.494 0 0 1-2.493 2.493h-10.43a3.365 3.365 0 0 1-3.362-3.363v-2.39a3.365 3.365 0 0 1 3.363-3.363");
}

.wc8hpep6u {
  cx: 31.522px;
  cy: 28.283px;
  r: 2.183px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
