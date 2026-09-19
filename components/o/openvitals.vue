<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gkitvrbmb"/><circle class="xydou237m"/><path class="cclo_sbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openvitals" /></template>
<style>
.cclo_sbjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.414 27.015c1.86-.13 2.78.773 4.29-1.757c1.724-2.646 3.182-5.324 6.744.788c3.158 6.335 3.542 4.267 5.718-1.424c2.578-7.29 5.555-6.887 8.833-.707c1.537 2.901 3.113 5.715 4.831 3.476c1.086-1.794 4.128-.873 7.17-1.13v3.015c-1.873.075-3.91-.784-5.33 1.855c-3.254 5.053-5.284 2.315-7.48-1.395c-3.734-6.65-4.628-2.934-5.68.546c-3.73 9.293-6.485 7.331-8.987 2.514c-1.145-2.45-2.045-4.349-3.276-3.521c-.606.56-4.377.178-6.833.252z");
}

.gkitvrbmb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.502 33.624c-4.6 7.613-14.027 10.948-22.456 7.776C7.24 38.086 2.3 28.718 4.536 19.58S15.48 4.416 24.82 5.542S41.186 14.592 41.186 24");
}

.xydou237m {
  cx: 19.127px;
  cy: 17.718px;
  r: 3.769px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
