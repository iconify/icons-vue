<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o2xprcc6o"/><path class="g2j6tjbww"/><path class="marvfte_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:securefolder" /></template>
<style>
.g2j6tjbww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.295h-39v18.72a2.18 2.18 0 0 0 2.16 2.2h34.66a2.18 2.18 0 0 0 2.18-2.18v-.02h0Z");
}

.marvfte_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.826 21.586a7.112 7.112 0 0 1 7.112 7.112h0a7.112 7.112 0 1 1-7.112-7.112Zm0 3.16a3.003 3.003 0 0 1 .719 5.928v1.896a.72.72 0 0 1-1.438.002v-1.898a3.003 3.003 0 0 1 .719-5.927Z");
}

.o2xprcc6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.68 13.015H24.77c-2-.1-5.93-4.23-8.19-4.23h-9.9a2.18 2.18 0 0 0-2.18 2.18v.05h0v7.29h39v-3.42a1.83 1.83 0 0 0-1.79-1.87Z");
}

</style>
