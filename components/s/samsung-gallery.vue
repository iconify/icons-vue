<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wly-7hb-l"/><path class="vgb2beb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-gallery" /></template>
<style>
.vgb2beb0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.65 27.403c-4.34-2.507-11.241-2.68-12.722-2.688c.042-.233.072-.47.072-.715c0-.246-.03-.484-.072-.717c1.492-.022 8.51-.253 12.723-2.685a5.379 5.379 0 0 0-5.379-9.317c-4.354 2.514-7.961 8.427-8.694 9.684a4 4 0 0 0-1.24-.718c.72-1.286 4.04-7.493 4.04-12.368a5.379 5.379 0 1 0-10.757 0c0 5.023 3.312 11.099 4.038 12.369a4 4 0 0 0-1.239.718c-.75-1.259-4.467-7.246-8.692-9.685a5.379 5.379 0 0 0-5.379 9.317c4.342 2.506 11.242 2.68 12.723 2.687c-.042.233-.072.47-.072.715c0 .246.03.484.072.717c-1.492.022-8.51.253-12.723 2.685a5.379 5.379 0 0 0 5.379 9.317c4.354-2.514 7.961-8.427 8.694-9.684c.365.31.78.555 1.24.719c-.719 1.285-4.04 7.493-4.04 12.367a5.379 5.379 0 1 0 10.757 0c0-5.023-3.312-11.098-4.038-12.369a4 4 0 0 0 1.239-.718c.75 1.259 4.467 7.246 8.692 9.685a5.379 5.379 0 1 0 5.379-9.317Z");
}

.wly-7hb-l {
  cx: 24px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

</style>
