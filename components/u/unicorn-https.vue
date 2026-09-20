<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fll3cdc1h"/><path class="r45br9ind"/><path class="s5d1dubwk"/><path class="buyr5ybga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unicorn-https" /></template>
<style>
.buyr5ybga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.194 36.762v-1.276c.012-4.042 6.105-4.042 6.118 0v1.276");
}

.fll3cdc1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.125 14.188l-5.855-4c-9.346 10.987-8.05 23.264 3.929 32.543");
}

.r45br9ind {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.612 4.152L20.57 14.3c-7.24 7.315-10.03 22.066-2.178 28.852c-4.542-8.13-1.205-21.008 11.15-14.892l3.85-5.143l-9.19-6.145z");
}

.s5d1dubwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.325 18.294l.837 2.78l2.217-.87zm9.864 18.467h8.134c.309 0 .56.248.56.555v5.977a.56.56 0 0 1-.56.555h-8.134a.557.557 0 0 1-.56-.554v-5.978c0-.307.25-.555.56-.555");
}

</style>
