<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="imy8urb-v"/><path class="ekye64p-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xnconvert" /></template>
<style>
.ekye64p-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.002 24.668c-4.888-10.914-16.015-4.789-16.257 2.16c-.29 8.375 12.449 12.278 16.314 2.387");
}

.imy8urb-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.081 25.21l6.512-6.14l-3.101-3.348c-.992-3.039 2.667-5.147 4.9-3.969l2.914 3.1l4.713-1.984V8.962c.868-2.976 5.21-2.914 6.201-.062v3.907l4.465 1.86l2.853-2.79c2.977-1.798 6.14 1.86 4.713 4.527l-2.667 2.667l6.14 6.015c1.054.869.93 2.357.248 3.101l-9.984 9.923c-4.444 3.995-12.593 4.385-17.426 0l-10.48-9.8c-.807-.868-.745-2.419 0-3.1");
}

</style>
