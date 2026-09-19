<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sw6-f8blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:scoreboard" /></template>
<style>
.sw6-f8blx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.072 17.405l7.05-10.424c.584-.864-.168-2.002-1.192-1.805L15.308 8.773L7.993 19.589a2.35 2.35 0 0 0 .63 3.266l10.817 7.314l21.397-4.132l-8.633 12.765l-18.622 3.596c-1.024.198-1.776-.941-1.192-1.805l7.05-10.424zl12.765 8.632");
}

</style>
