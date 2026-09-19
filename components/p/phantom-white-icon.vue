<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s2yovib8j"/><path class="zsu9mropi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:phantom-white-icon" /></template>
<style>
.s2yovib8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.857 21.357V42.5c-4.945-5.039-10.912-5.039-15.857 0c-4.945-5.039-10.912-5.039-15.857 0V21.357C9.458.214 38.53.214 39.857 21.357");
}

.zsu9mropi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.399 17.399c2.185 0 3.958 1.773 3.958 3.958s-1.774 3.97-3.958 3.97c-2.197 0-3.97-1.785-3.97-3.97s1.773-3.958 3.97-3.958m13.214 0c2.185 0 3.958 1.773 3.958 3.958s-1.773 3.97-3.958 3.97c-2.197 0-3.97-1.785-3.97-3.97s1.773-3.958 3.97-3.958m-1.938 14.119c-1.738 3.57-7.611 3.57-9.397 0");
}

</style>
