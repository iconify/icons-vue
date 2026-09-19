<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="zyxuxxbwx"/><path class="os2t6i80i"/><path class="lui5jqb7b"/><path class="u2ngmb3oy"/><path class="mlvn18b2s"/><path class="zoux3ybqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zoom-earth" /></template>
<style>
.lui5jqb7b {
  d: path("M28.537 25.473c1.663-5.282-4.44-10.826-12.326-9.552c-5.428.877-12.88 7.51-11.377 17.731");
}

.mlvn18b2s {
  d: path("M22.527 28.537c5.282 1.663 10.826-4.44 9.552-12.326c-.877-5.428-7.51-12.88-17.731-11.377");
}

.os2t6i80i {
  d: path("M19.463 22.527C17.8 27.81 23.903 33.353 31.79 32.08c5.45-.88 12.938-7.561 11.36-17.851");
}

.u2ngmb3oy {
  d: path("M24.993 19.334c-5.131-1.163-10.308 4.807-9.072 12.455c.877 5.428 7.51 12.88 17.731 11.378");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zoux3ybqb {
  d: path("M28.768 24a4.768 4.768 0 1 1-9.536 0a4.768 4.768 0 0 1 9.536 0");
}

.zyxuxxbwx {
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
