<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wz3bh0b9h"/><path class="gkut6vbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:traveloka" /></template>
<style>
.gkut6vbxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.163 34.204c-5.321-6.166-5.673-16.399-4.989-25.396");
}

.wz3bh0b9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.174 19.238C31.03 16.518 43.5 12.89 43.5 13.343c-18.006 21.57-13.372 18.892-4.535 25.849c-9.873-4.623-19.5-3.586-22.22-7.256c-2.529-4.197-6.238-4.7-12.245-5.895c4.708.557 4.977 1.629 8.163.453c2.821-1.152 6.284 1.172 6.852-.453c.64-1.83-.934-7.242-.813-10.624c.53-3.25 4.367-4.642 8.472-6.609");
}

</style>
