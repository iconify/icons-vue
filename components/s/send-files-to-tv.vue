<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yodbz3-qi"/><path class="fgkg9ab5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:send-files-to-tv" /></template>
<style>
.fgkg9ab5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.945 11.913l4.756-2.277l2.278 4.756m-2.278-4.756L17.639 24m12.416 12.087l-4.756 2.277l-2.278-4.756m2.278 4.756L30.361 24");
}

.yodbz3-qi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4M5.5 24h37");
}

</style>
