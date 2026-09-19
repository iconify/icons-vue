<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dy--5_rim"/><path class="d_7u1nbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yoke" /></template>
<style>
.d_7u1nbal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.9 24.5H27v6h-6.1zm0 9.4h6.2m8-18.3h3.7m-3.7 4.7h3.7M35.1 25h3.7m-26 0H9.2m3.6-4.7H9.2m3.6-4.7H9.2");
}

.dy--5_rim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.8 33.9V14.1c4.3-1.6 1.9-5.9 0-5.9H7.3A2.62 2.62 0 0 0 4.5 11v20.9a7.8 7.8 0 0 0 8.2 8h22.9a7.81 7.81 0 0 0 7.8-7.5V10.5a2.42 2.42 0 0 0-2.6-2.4H35c-1.9 0-4.1 4.8 0 5.9v19.8h-3.3v-9.6c0-2.9-1.7-4.5-4.5-4.5h-6.7a4.12 4.12 0 0 0-4.2 4.3v9.8h-3.5Z");
}

</style>
