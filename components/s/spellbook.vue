<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nmuf57z6j"/><path class="t8k5gga1j"/><path class="n1tbyabld"/><path class="i3euud1wo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spellbook" /></template>
<style>
.i3euud1wo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.16 17.59l-10 .64l3.93 9.88zm-6.07 10.52l6.07 7.44l-10-5.78zm12.15 0l-6.08 7.44l10-5.78zm-6.08-15.66v5.14");
}

.n1tbyabld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.16 17.59l-6.07 10.52h12.15zm6.08 10.52l3.92-9.88l-10-.64z");
}

.nmuf57z6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.45v35.1a2 2 0 0 0 1.95 2h2.38V4.5h-2.38A2 2 0 0 0 8.4 6.45m4.33-1.95v39h24.92a2 2 0 0 0 2-2V6.45a2 2 0 0 0-2-1.95Z");
}

.t8k5gga1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.16 12.45l10 5.78v11.54l-10 5.78l-10-5.78V18.23z");
}

</style>
