<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="vwm1rlbqq"/><path class="sj7m7dfkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sort-collector" /></template>
<style>
.sj7m7dfkv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.365 27.18H7.193a2.693 2.693 0 1 0 0 5.386h1.12m11.275-2.692a2.693 2.693 0 1 0-5.386 0m7.105-16.367a2.693 2.693 0 1 0 5.386 0V10.41a2.693 2.693 0 1 0-5.386 0zM24 16.2v4.077m15.635 6.903h1.172a2.693 2.693 0 1 1 0 5.386h-1.12m-11.275-2.692a2.693 2.693 0 1 1 5.386 0m-1.629 10.403v-2.565a2.705 2.705 0 0 0-3.145-2.677c-1.584.264-3.489.513-5.024.513s-3.44-.25-5.024-.513a2.705 2.705 0 0 0-3.145 2.677v2.565");
}

.vwm1rlbqq {
  width: 31.373px;
  height: 20.006px;
  x: 8.313px;
  y: 20.277px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.798px;
  ry: 7.798px;
}

</style>
