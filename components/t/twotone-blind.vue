<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="g-76lbcql"/><path class="px8q-bciz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-blind" /></template>
<style>
.g-76lbcql {
  cx: 11.5px;
  cy: 3.5px;
  r: 2px;
  fill: currentColor;
}

.px8q-bciz {
  fill: currentColor;
  d: path("M12.13 7.12c-.17-.35-.44-.65-.8-.85a1.98 1.98 0 0 0-1.93-.03v-.01L4 9.3V14h2v-3.54l1.5-.85C7.18 10.71 7 11.85 7 13v5.33L4.4 21.8L6 23l3-4l.22-3.54L11 18v5h2v-6.5l-1.97-2.81c-.04-.52-.14-1.76.45-3.4c.75 1.14 1.88 1.98 3.2 2.41L20.63 23l.87-.5l-5.48-9.5H17v-2c-.49 0-2.88.17-4.08-2.21");
}

</style>
