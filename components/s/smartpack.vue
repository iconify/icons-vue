<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jui7fvb8i"/><rect class="mjtxlvbxt"/><path class="v6_oagb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smartpack" /></template>
<style>
.jui7fvb8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.23 26a17 17 0 0 0 .14-2a17 17 0 0 0-.14-2l4.33-3.39a1 1 0 0 0 .25-1.31l-4.1-7.11a1 1 0 0 0-1.25-.44l-5.11 2.06a16 16 0 0 0-3.46-2l-.77-5.43a1 1 0 0 0-1-.86H19.9a1 1 0 0 0-1 .86l-.77 5.43a15.3 15.3 0 0 0-3.46 2L9.54 9.75a1 1 0 0 0-1.25.44l-4.1 7.11a1 1 0 0 0 .25 1.31L8.76 22a17 17 0 0 0-.14 2a17 17 0 0 0 .14 2l-4.32 3.39a1 1 0 0 0-.25 1.31l4.1 7.11a1 1 0 0 0 1.25.44l5.11-2.06a16 16 0 0 0 3.46 2l.77 5.43a1 1 0 0 0 1 .86h8.2a1 1 0 0 0 1-.86l.77-5.43a15.3 15.3 0 0 0 3.46-2l5.11 2.06a1 1 0 0 0 1.25-.44l4.1-7.11a1 1 0 0 0-.25-1.31Z");
}

.mjtxlvbxt {
  width: 12px;
  height: 12px;
  x: 18px;
  y: 18px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

.v6_oagb2f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.09 18v-3m5.82 3v-3M30 21.09h3m-3 5.82h3M26.91 30v3m-5.82-3v3M18 26.91h-3m3-5.82h-3");
}

</style>
