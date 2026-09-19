<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4kl-cc5o"/><circle class="nqc7ndjui"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uala" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.nqc7ndjui {
  cx: 37.646px;
  cy: 27.475px;
  r: 0.75px;
  fill: currentColor;
}

.r4kl-cc5o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.125 19.775v8h4m-18.521-8v5.3c0 1.5 1.2 2.7 2.6 2.7s2.7-1.2 2.7-2.7v-5.3m6.103 5.3h-3.6m-.9 2.7l2.7-8l2.7 8m12.628-2.7h-3.6m-.9 2.7l2.7-8l2.7 8");
}

</style>
