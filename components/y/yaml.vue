<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":176};
const content = `<path class="qnjal4bfh"/><path class="cia0lmbof"/><path class="af7a4wz_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:yaml" /></template>
<style>
.af7a4wz_p {
  stroke: var(--svg-color--000, #000);
  d: path("M117.109.803h38.536L40.036 174.216H1.5l57.805-86.707L1.5.803h38.536l38.537 57.804zM49.67 174.216h38.537l77.072-115.609v115.609h38.536V.803h-38.536zm162.174 0h38.536V58.607l38.536 57.805l38.537-57.805v115.609h38.536V.803h-48.17l-28.903 57.804L250.38.803h-38.536zm163.779 0H510.5l-25.691-38.536h-70.65V.803h-38.536z");
}

.cia0lmbof {
  d: path("M414.962 0H116.68L0 175.019h512L414.962 29.46zm-1.606 1.606v28.342L509 173.413H3L117.539 1.606z");
}

.qnjal4bfh {
  fill: var(--svg-color--fff, #fff);
  d: path("M117.109.803h297.05v28.902L510.5 174.216H1.5z");
}

</style>
