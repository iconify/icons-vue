<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3yagibey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-party-mode" /></template>
<style>
.r3yagibey {
  fill: currentColor;
  d: path("M22 4h-5.17L15 2H9L7.17 4H2v16h20zM12 7c1.63 0 3.06.79 3.98 2H12c-1.66 0-3 1.34-3 3c0 .35.07.69.18 1H7.1A5.002 5.002 0 0 1 12 7m0 10c-1.63 0-3.06-.79-3.98-2H12c1.66 0 3-1.34 3-3c0-.35-.07-.69-.18-1h2.08a5.002 5.002 0 0 1-4.9 6");
}

</style>
