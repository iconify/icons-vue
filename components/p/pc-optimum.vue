<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q1pun8b4t"/><path class="yq5l-fbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pc-optimum" /></template>
<style>
.q1pun8b4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.762 21.755c-.053 4.151.099 14.298 3.929 16.55c1.829 1.076.169-9.31-3.423-13.695c-4.764-5.815-16.63-9.193-13.133-10.978c8.968-4.577 22.113-5.553 22.376.807c.163 3.924-3.525 6.633-12.045 11.655");
}

.yq5l-fbmw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.581 10.921l-1.405-1.304C18.587 13.706 18.5 40.34 42.5 21.513");
}

</style>
