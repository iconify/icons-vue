<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jryael24t"/><path class="vecy6kdjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mico" /></template>
<style>
.jryael24t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.554 39.393c1.125.061 1.38-.24 1.995-1.435l8.604-16.733c.73-1.422.355-2.628-1.576-2.734l-19.1-1.045c-1.124-.07-1.38.24-1.995 1.435L10.88 35.614c-.73 1.421-.356 2.628 1.575 2.733z");
}

.vecy6kdjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.522 30.556c1.126.061 1.38-.24 1.996-1.435l8.603-16.733c.73-1.422.356-2.628-1.575-2.734l-19.1-1.045c-1.125-.07-1.38.24-1.995 1.435L5.847 26.777c-.73 1.421-.355 2.628 1.576 2.733z");
}

</style>
