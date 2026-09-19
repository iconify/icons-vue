<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ywybb-bok"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:symbol-ampersand" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ywybb-bok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.53 35.123h-1.88a3.9 3.9 0 0 1-3.148-1.603l-7.715-10.606c-.992-1.302-2.736-3.016-2.736-5.555c0-2.398 1.947-4.482 4.656-4.482c2.637 0 4.508 2.084 4.508 4.482c0 2.539-2.057 4.71-5.859 5.43c-4.238.804-6.886 3.13-6.886 6.963c0 3.099 1.953 5.37 5.859 5.37c5.133 0 8.155-4.867 12.618-10.85");
}

</style>
