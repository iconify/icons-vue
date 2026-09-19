<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vwd8_qllq"/><circle class="z-n9e68gk"/><g class="tybcrmi-m"><circle class="wocnhmpex"/><path class="rr43gbc5x"/><path class="xjljxmblz"/></g><path class="a6_9t1osd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:mantelpiece-clock" /></template>
<style>
.a6_9t1osd {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M3 53h8v2H3zm50 0h8v2h-8z");
}

.rr43gbc5x {
  d: path("M40.1 30c.7 0 2.9-2 2.9-2s-2.2-2-2.9-2c-.6 0-1.1.6-1.3 1.4H31v1.2h7.8c.2.8.7 1.4 1.3 1.4");
}

.tybcrmi-m {
  fill: var(--svg-color--333, #333);
}

.vwd8_qllq {
  fill: var(--svg-color--594640, #594640);
  d: path("M60 40c-5 0-9-8-9-13c0-10-9-18-19-18s-19 8-19 18c0 5-4 13-9 13H0v13h64V40z");
}

.wocnhmpex {
  cx: 32px;
  cy: 28px;
  r: 2px;
}

.xjljxmblz {
  d: path("m32 13.7l-1 14h2z");
}

.z-n9e68gk {
  cx: 32px;
  cy: 28px;
  r: 15px;
  fill: var(--svg-color--fed0ac, #fed0ac);
}

</style>
