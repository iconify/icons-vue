<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="sl9anikdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mizuho-direct" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.sl9anikdr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.569 28.423c7.926-.767 17.613-.49 23.931.686m-20.584-9.511v5.449M9.5 25.04v-6.149l3.183 6.157l3.183-6.147v6.147m3.867-5.45h3.737l-3.737 5.45h3.737m5.504-5.45v5.449m3.736-5.449v5.449m-3.736-2.734h3.736m-7.472-2.715v3.645c0 .997.836 1.805 1.868 1.805h1.868m7.422-5.45c1.031 0 1.868.808 1.868 1.805v1.84c0 .997-.837 1.805-1.869 1.805h0c-1.031 0-1.868-.808-1.868-1.806v-1.84c0-.996.837-1.805 1.868-1.805");
}

</style>
