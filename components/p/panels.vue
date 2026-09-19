<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g_h4veben"/><path class="r7tke_58l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:panels" /></template>
<style>
.g_h4veben {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.996 24c0 1.57 0 4.606.24 6.206c.252 1.685 9.118 13.294 12.19 13.294s3.072-13.563 3.072-19.5s0-19.5-3.072-19.5s-11.938 11.609-12.19 13.294c-.24 1.6-.24 4.637-.24 6.206m21.481-12.633c1.483-1.164 2.83-1.963 3.697-1.963c2.83 0 2.83 10.157 2.83 14.596s0 14.596-2.83 14.596c-.867 0-2.214-.8-3.697-1.963");
}

.r7tke_58l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.88 9.986c1.713-1.484 3.322-2.545 4.315-2.545c3.012 0 3.012 11.515 3.012 16.559s0 16.558-3.013 16.558c-.992 0-2.601-1.061-4.313-2.545");
}

</style>
