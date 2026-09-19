<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="r_7krfq8k"/><path class="y41qjpcbb"/></g><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pleco" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.r_7krfq8k {
  d: path("M12.073 20.34C18.685 16 23.085 11.792 24.78 7.748");
}

.y41qjpcbb {
  d: path("m20.333 13.871l10.743-1.617l-9.01 9.242l-7.163.52l3.35 11.494l13.055-1.733l2.714-11.898l-9.3 1.213l-.692 11.552m-4.16-5.545l9.011-1.387m-17.617 9.416l-3.53 6.822m8.786-5.378l3.582 3.985m4.909-4.274l3.582 4.332m5.372-5.199l6.301 6.468M24.723 21.091l-2.657.405");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
