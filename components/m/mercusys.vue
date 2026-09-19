<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hfvcltbgn"/><path class="xuu9vobrf"/><path class="x24ewtzdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mercusys" /></template>
<style>
.hfvcltbgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h8.782c0-7.048-5.734-12.782-12.782-12.782V38.5a4 4 0 0 0 4 4");
}

.x24ewtzdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v4.915c15.486 0 28.085 12.599 28.085 28.085H38.5a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.xuu9vobrf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.282 42.5h7.303c0-13.28-10.805-24.085-24.085-24.085v7.303c9.254 0 16.782 7.528 16.782 16.782");
}

</style>
